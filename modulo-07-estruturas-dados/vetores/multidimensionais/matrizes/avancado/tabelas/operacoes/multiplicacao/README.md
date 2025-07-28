# Multiplicação de Matrizes

Bem-vindo(a) a mais uma etapa do nosso curso de lógica de programação!

Hoje vamos mergulhar em um dos conceitos mais importantes e usados em programação e matemática: **multiplicação de matrizes**.

Pode parecer complicado à primeira vista, mas com exemplos práticos e um passo a passo, você vai ver que é totalmente possível dominar esse assunto!

---

## O que é uma matriz?

Antes de tudo, lembre-se: uma matriz nada mais é do que uma tabela de números, organizada em linhas e colunas. Por exemplo:

```plaintext
[ 1  2  3 ]
[ 4  5  6 ]
```

Essa é uma matriz de 2 linhas por 3 colunas (2x3).

---

## Quando multiplicar matrizes?

Multiplicar matrizes é útil quando queremos combinar informações de duas tabelas diferentes para gerar um novo resultado.

Por exemplo, em jogos, gráficos, inteligência artificial e até em planilhas do dia a dia!

---

## Como funciona a multiplicação de matrizes?

Para multiplicar duas matrizes, precisamos seguir algumas regras:

- Só é possível multiplicar uma matriz **A** de tamanho `m x n` por uma matriz **B** de tamanho `n x p`. Ou seja, o número de colunas da primeira matriz deve ser igual ao número de linhas da segunda matriz.
- O resultado será uma nova matriz de tamanho `m x p`.

### Exemplo prático

Vamos multiplicar as matrizes abaixo:

Matriz A (2x3):

```plaintext
[ 1  2  3 ]
[ 4  5  6 ]
```

Matriz B (3x2):

```plaintext
[ 7   8 ]
[ 9  10 ]
[11  12 ]
```

**Passo a passo:**

1. Pegue a primeira linha da Matriz A e a primeira coluna da Matriz B.
2. Multiplique os elementos correspondentes e some os resultados.

Exemplo para o elemento [1,1] da matriz resultado:

```plaintext
(1*7) + (2*9) + (3*11) = 7 + 18 + 33 = 58
```

Repita para todos os elementos!

---

## Código exemplo em JavaScript

```js
function multiplicarMatrizes(A, B) {
    let linhasA = A.length;
    let colunasA = A[0].length;
    let colunasB = B[0].length;
    let resultado = [];

    for (let i = 0; i < linhasA; i++) {
        resultado[i] = [];
        for (let j = 0; j < colunasB; j++) {
            let soma = 0;
            for (let k = 0; k < colunasA; k++) {
                soma += A[i][k] * B[k][j];
            }
            resultado[i][j] = soma;
        }
    }
    return resultado;
}

// Testando:
let A = [
    [1, 2, 3],
    [4, 5, 6]
];
let B = [
    [7, 8],
    [9, 10],
    [11, 12]
];

console.log(multiplicarMatrizes(A, B));
```

---

## Explorando mais

Se quiser se aprofundar, confira a pasta [`/conceitos`](../conceitos/README.md) para entender mais sobre matrizes, operações e aplicações no mundo real!

---

## O que entendi?

> Escreva aqui, com suas próprias palavras, o que você entendeu sobre multiplicação de matrizes. Use exemplos do seu dia a dia ou crie analogias para fixar o conteúdo!
