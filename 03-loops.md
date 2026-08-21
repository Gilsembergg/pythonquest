# 🔁 03 — Loops

Loops permitem repetir um determinado trecho de código.

Um dos mais utilizados em Python é o `for`:

```python
for numero in range(5):
    print(numero)
```

Esse código imprime os números de `0` até `4`.

Também podemos utilizar `while` quando queremos repetir algo enquanto uma condição for verdadeira:

```python
contador = 0

while contador < 3:
    print(contador)
    contador += 1
```

## 🧩 Desafio

Quantas vezes `"Olá!"` será exibido?

```python
for i in range(3):
    print("Olá!")
```

* [ ] 1 vez
* [ ] 2 vezes
* [ ] 3 vezes
* [ ] 4 vezes

<details>
<summary>💡 Ver resposta</summary>

**3 vezes.**

`range(3)` gera os valores `0`, `1` e `2`, fazendo o loop executar três vezes.

</details>

[⬅️ Condicionais](02-condicionais.md) | [Próximo: Desafio Final ➡️](04-desafio-final.md)
