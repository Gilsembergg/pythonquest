# 🔀 02 — Condicionais

Condicionais permitem que o programa tome decisões de acordo com determinadas condições.

Em Python, usamos principalmente `if`, `elif` e `else`.

```python
idade = 18

if idade >= 18:
    print("Maior de idade")
else:
    print("Menor de idade")
```

Se a condição do `if` for verdadeira, seu bloco será executado. Caso contrário, o bloco do `else` será executado.

## 🧩 Desafio

O que será exibido?

```python
numero = 7

if numero % 2 == 0:
    print("Par")
else:
    print("Ímpar")
```

* [ ] Par
* [ ] Ímpar
* [ ] 7
* [ ] Erro

<details>
<summary>💡 Ver resposta</summary>

**Ímpar.**

O operador `%` retorna o resto da divisão. Como `7 % 2` resulta em `1`, o número é ímpar.

</details>

[⬅️ Variáveis](01-variaveis.md) | [Próximo: Loops ➡️](03-loops.md)
