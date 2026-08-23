# Resolução de conflito

Durante o desenvolvimento do projeto Python Quest, foi realizado um exercício prático de resolução de conflito utilizando Git.

## Como o conflito foi criado

Primeiramente, o branch `aprendizados` recebeu uma alteração no arquivo `README.md`, relacionada à seção de status do projeto.

Depois, o branch `main` recebeu uma alteração diferente na mesma parte do arquivo `README.md`.

Ao executar o comando:

```bash
git merge aprendizados
```

estando no branch `main`, o Git identificou alterações conflitantes no mesmo trecho do arquivo.

O terminal apresentou a mensagem:

```text
CONFLICT (content): Merge conflict in README.md
Automatic merge failed; fix conflicts and then commit the result.
```

## Identificação do conflito

O comando:

```bash
git diff
```

permitiu visualizar o trecho em conflito, identificado pelos marcadores:

```text
<<<<<<< HEAD
=======
>>>>>>> aprendizados
```

Esses marcadores indicavam que existiam duas versões diferentes para o mesmo trecho do `README.md`.

## Resolução

O conflito foi resolvido manualmente no arquivo `README.md`, escolhendo uma versão adequada para a seção de status do projeto e removendo os marcadores de conflito.

Depois da alteração, o arquivo foi adicionado novamente ao controle de versão com:

```bash
git add README.md
```

Em seguida, foi realizado o commit da resolução:

```bash
git commit -m "Resolve README merge conflicts"
```

## Verificação

Após a resolução, foi utilizado o comando:

```bash
grep -nE '<<<<<<<|=======|>>>>>>>' README.md
```

O comando não apresentou nenhuma saída, confirmando que os marcadores de conflito haviam sido removidos.

Também foi utilizado:

```bash
git status
```

que apresentou:

```text
nothing to commit, working tree clean
```

## Aprendizado

A atividade permitiu compreender na prática como conflitos surgem quando diferentes branches modificam a mesma parte de um arquivo. Também foi possível aprender a identificar os marcadores de conflito, escolher o conteúdo correto e finalizar a integração utilizando um commit de merge.
