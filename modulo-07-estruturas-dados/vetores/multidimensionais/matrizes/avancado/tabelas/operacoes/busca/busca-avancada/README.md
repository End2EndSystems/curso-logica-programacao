# Busca Avançada em Matrizes

Bem-vindo(a) a mais uma aula do nosso curso de lógica de programação!

Hoje vamos explorar como buscar informações em **matrizes** (ou tabelas multidimensionais) de forma mais avançada.

Prepare-se para aprender técnicas que vão turbinar suas habilidades!

---

## O que é uma Busca em Matrizes?

Buscar em matrizes significa procurar por um valor específico (ou um conjunto de valores) dentro de uma tabela com linhas e colunas.

Isso é muito útil quando trabalhamos com dados organizados, como notas de alunos, tabelas de jogos, ou até mapas de jogos!

---

## Tipos de Busca

### 1. Busca Simples

A busca simples percorre cada elemento da matriz até encontrar o que você procura.

```js
let matriz = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
];

let encontrado = false;
let valorProcurado = 5;

for (let i = 0; i < matriz.length; i++) {
    for (let j = 0; j < matriz[i].length; j++) {
        if (matriz[i][j] === valorProcurado) {
            encontrado = true;
            console.log(`Valor encontrado na posição [${i}][${j}]`);
        }
    }
}
if (!encontrado) {
    console.log("Valor não encontrado.");
}
```

### 2. Busca por Condição

Às vezes, queremos encontrar todos os elementos que atendem a uma condição, como todos os números pares.

```js
for (let i = 0; i < matriz.length; i++) {
    for (let j = 0; j < matriz[i].length; j++) {
        if (matriz[i][j] % 2 === 0) {
            console.log(`Número par encontrado: ${matriz[i][j]} na posição [${i}][${j}]`);
        }
    }
}
```

---

## Busca Otimizada

Se a matriz estiver **ordenada** (por exemplo, cada linha está em ordem crescente), podemos usar técnicas mais rápidas, como a **busca binária** em cada linha.

Para se aprofundar nesse conceito, veja o arquivo [`busca-binaria/README.md`](../busca-binaria/README.md).

---

## Desafios Comuns

- **Matrizes grandes**: quanto maior a matriz, mais demorado pode ser encontrar o que você procura.
- **Vários resultados**: pode haver mais de uma ocorrência do valor buscado.
- **Condições complexas**: às vezes, a busca envolve mais de uma condição (ex: números pares maiores que 5).

---

## Exercício Prático

1. Crie uma matriz 4x4 com números aleatórios de 1 a 20.
2. Peça para o usuário digitar um número.
3. Informe se o número está na matriz e, se sim, em quais posições.

---

## Explorando Mais

- [Busca Binária em Matrizes](./busca-binaria/README.md)
- [Filtrando Dados em Matrizes](./filtros/README.md)

---

## O que entendi?

> Escreva aqui, com suas próprias palavras, o que você entendeu sobre busca avançada em matrizes. Dê exemplos, explique para você mesmo(a) como faria uma busca e por que isso é importante!
