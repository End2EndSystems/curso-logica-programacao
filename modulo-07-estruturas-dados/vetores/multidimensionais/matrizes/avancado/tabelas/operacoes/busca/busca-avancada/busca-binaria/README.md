# Busca Binária em Matrizes

## Introdução

Você já imaginou procurar um nome em uma lista telefônica gigante?

Se ela estiver organizada em ordem alfabética, fica muito mais fácil, certo?

É isso que a **busca binária** faz: ela aproveita a ordem dos dados para encontrar o que você procura rapidinho!

Nesta aula, vamos aprender como aplicar a busca binária em **matrizes** (ou tabelas), tornando a busca por informações muito mais eficiente.

---

## O que é Busca Binária?

A busca binária é um algoritmo que divide o problema pela metade a cada passo. Funciona assim:

1. Olhe para o elemento do meio.
2. Se for o que você procura, parabéns!
3. Se o que você procura é menor, repita o processo na metade da esquerda.
4. Se for maior, repita na metade da direita.
5. Repita até encontrar ou acabar as opções.

> **Importante:** Para usar busca binária, os dados precisam estar **ordenados**!

Quando falamos de matrizes (ou tabelas), podemos aplicar a busca binária de algumas formas diferentes, dependendo de como os dados estão organizados:

- **Matriz ordenada por linhas:** Cada linha está em ordem crescente.
- **Matriz totalmente ordenada:** Todos os elementos estão em ordem crescente, como se fosse uma lista gigante.

Vamos ver exemplos práticos!

---

### Exemplo 1: Busca Binária em Cada Linha

Imagine a matriz abaixo, onde cada linha está ordenada:

```markdown
|  1 |  3 |  5 |  7 |
|  9 | 11 | 13 | 15 |
| 17 | 19 | 21 | 23 |
```

Se você quiser procurar o número 13, pode aplicar a busca binária **apenas na linha onde ele pode estar**.

#### Passos

1. Escolha a linha (ou faça uma busca binária nas linhas também!).
2. Aplique a busca binária na linha escolhida.

---

### Exemplo 2: Matriz como Vetor

Se a matriz está totalmente ordenada, podemos "imaginar" que ela é um vetor (lista) e aplicar a busca binária normalmente, convertendo os índices.

#### Como converter?

Se a matriz tem `n` colunas:

- Índice no vetor: `i`
- Linha: `i / n`
- Coluna: `i % n`

---

## Vantagens da Busca Binária

- **Muito rápida:** Reduz o número de comparações drasticamente.
- **Eficiente para grandes volumes de dados.**

---

## Desvantagens

- **Só funciona em dados ordenados.**
- Se os dados mudam muito, pode ser difícil manter a ordem.

---

## Praticando

Tente implementar a busca binária em uma matriz no seu código! Experimente com diferentes tamanhos e veja como o número de passos diminui em relação à busca simples.

---

## O que entendi?

> Escreva aqui, com suas próprias palavras, o que você entendeu sobre busca binária em matrizes. Como você explicaria para um amigo? O que achou mais interessante ou difícil?
