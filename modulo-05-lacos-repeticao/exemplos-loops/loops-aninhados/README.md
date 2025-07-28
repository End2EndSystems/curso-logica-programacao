# Loops Aninhados

Bem-vindo à aula sobre **loops aninhados**!

Aqui, vamos explorar como usar um loop dentro de outro loop para resolver problemas mais complexos e interessantes.

Prepare-se para dar um passo além nos seus códigos!

---

## O que são Loops Aninhados?

Loops aninhados são quando você coloca um loop (como `for` ou `while`) dentro de outro.

Isso é super útil quando precisamos trabalhar com estruturas em duas dimensões, como tabelas, matrizes ou até para criar padrões visuais.

### Exemplo Básico

```python
for i in range(3):
    for j in range(2):
        print(f"i={i}, j={j}")
```

**O que acontece aqui?**

- O loop externo (`i`) roda 3 vezes.
- Para cada vez que o externo roda, o interno (`j`) roda 2 vezes.
- Ou seja, o código dentro dos dois loops será executado 6 vezes no total!

---

## Para que servem Loops Aninhados?

- **Tabuada:** Quer mostrar a tabuada de todos os números de 1 a 10? Loops aninhados!
- **Matrizes:** Precisa percorrer linhas e colunas de uma tabela? Loops aninhados!
- **Desenhar padrões:** Quer criar desenhos com asteriscos no console? Loops aninhados!

---

## Exercício Prático

Vamos criar uma tabuada completa usando loops aninhados:

```python
for i in range(1, 11):
    for j in range(1, 11):
        print(f"{i} x {j} = {i*j}")
    print("-" * 15)
```

Tente rodar esse código e veja como fica organizado!

---

## Dicas Importantes

- Cuidado para não se perder nos índices! Use nomes de variáveis diferentes para cada loop.
- Loops aninhados podem deixar o código mais lento se usados em excesso. Use com sabedoria!
- Sempre pense: "Preciso mesmo de dois loops aqui?"

---

## Desafio

Crie um programa que desenhe um quadrado de asteriscos de tamanho 5x5, assim:

```text
*****
*****
*****
*****
*****
```

Dica: Use dois loops `for`!

---

## O que entendi?

> Escreva aqui, com suas palavras, o que você entendeu sobre loops aninhados. Como você usaria isso em um jogo ou aplicativo? Quais dúvidas ainda ficaram?
