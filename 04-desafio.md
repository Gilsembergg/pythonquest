# 🏆 Desafio Final

Chegou a hora de juntar os conceitos apresentados nos módulos anteriores.

## 🎯 Desafio

Crie um programa que:

1. Pergunte o nome do usuário.
2. Pergunte a idade.
3. Informe se o usuário é maior ou menor de idade.
4. Mostre uma mensagem utilizando o nome informado.

### 💻 Exemplo

Para as entradas:

```text
Nome: Ana
Idade: 20
```

O programa deve produzir algo parecido com:

```text
Olá, Ana!
Você é maior de idade.
```

### 🧠 Dica

Você pode utilizar:

* variáveis;
* `input()`;
* `if` e `else`;
* `print()`.

Tente resolver sozinho antes de consultar uma possível solução.

<details>
<summary>💡 Ver solução</summary>

```python
nome = input("Nome: ")
idade = int(input("Idade: "))

if idade >= 18:
    print(f"Olá, {nome}!")
    print("Você é maior de idade.")
else:
    print(f"Olá, {nome}!")
    print("Você é menor de idade.")
```

</details>

## 🎉 Parabéns!

Se você conseguiu completar o desafio, você já teve contato com alguns dos principais fundamentos da programação em Python.

[⬅️ Voltar aos Loops](03-loops.md) | [🏠 Página inicial](README.md)
