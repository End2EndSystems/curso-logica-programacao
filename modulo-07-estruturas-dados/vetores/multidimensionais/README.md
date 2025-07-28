# Vetores Multidimensionais

Bem-vindo(a) a mais uma etapa da sua jornada em lógica de programação!

Hoje vamos explorar um conceito que pode parecer complicado à primeira vista, mas que vai abrir muitas portas para resolver problemas mais complexos: **vetores multidimensionais**.

## O que são Vetores Multidimensionais?

Até agora, você já viu vetores (ou arrays) simples, que são como uma fila de caixas, onde cada caixa guarda um valor.

Mas e se cada caixa pudesse guardar outra fila de caixas? Ou até mais?

É aí que entram os vetores multidimensionais!

Um vetor multidimensional nada mais é do que um vetor que guarda outros vetores.

O exemplo mais comum é a **matriz**, que é um vetor de duas dimensões (linhas e colunas).

### Exemplo Visual

Imagine uma tabela do Excel: cada célula pode ser acessada por uma linha e uma coluna.

Assim funciona uma matriz!

```plaintext
[ [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9] ]
```

Aqui temos uma matriz 3x3 (3 linhas e 3 colunas).

## Como Declarar e Usar em Código

### Em JavaScript

```js
let matriz = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
];

// Acessando o elemento da segunda linha, terceira coluna:
console.log(matriz[1][2]); // Saída: 6
```

### Em Python

```python
matriz = [
        [1, 2, 3],
        [4, 5, 6],
        [7, 8, 9]
]

# Acessando o elemento da segunda linha, terceira coluna:
print(matriz[1][2])  # Saída: 6
```

## Para que servem?

- **Jogos**: Tabuleiros, mapas, grades.
- **Planilhas**: Guardar dados em linhas e colunas.
- **Imagens**: Cada pixel pode ser representado por uma matriz de cores.
- **Resolução de problemas matemáticos**: Matrizes são essenciais em álgebra linear.

## Explorando Mais Fundo

Se quiser se aprofundar em matrizes, veja a pasta [`matrizes`](./matrizes/README.md) para exemplos práticos, exercícios e desafios!

## Dicas para Não Se Perder

- Sempre pense em linhas e colunas.
- O primeiro índice é a linha, o segundo é a coluna: `matriz[linha][coluna]`.
- Use loops aninhados para percorrer todos os elementos.

## Exercício Rápido

Crie uma matriz 2x3 e preencha com números de 1 a 6. Depois, imprima todos os elementos usando dois loops.

## O que entendi?

> Escreva aqui, com suas próprias palavras, o que você entendeu sobre vetores multidimensionais. Use exemplos do seu dia a dia para ajudar a fixar o conceito!
