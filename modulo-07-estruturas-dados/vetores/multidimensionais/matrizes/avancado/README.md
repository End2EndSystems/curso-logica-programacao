# Matrizes Avançado

Bem-vindo(a) à aula avançada sobre **matrizes**!

Se você chegou até aqui, já sabe o que são vetores e matrizes básicas.

Agora, vamos explorar como as matrizes podem ser usadas para resolver problemas mais complexos e interessantes.

---

## O que são Matrizes Avançadas?

Matrizes avançadas vão além do simples armazenamento de dados em linhas e colunas.

Aqui, você vai aprender a manipular, percorrer, transformar e até mesmo criar algoritmos que usam matrizes para resolver desafios do mundo real, como jogos, imagens e tabelas dinâmicas.

---

## Revisando: O que é uma Matriz?

Uma matriz é uma estrutura de dados bidimensional, ou seja, uma tabela com linhas e colunas. Por exemplo:

```js
let matriz = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
];
```

---

## Operações Avançadas com Matrizes

### 1. Percorrendo Matrizes

Para acessar todos os elementos de uma matriz, usamos dois loops (um para linhas, outro para colunas):

```js
for (let i = 0; i < matriz.length; i++) {
    for (let j = 0; j < matriz[i].length; j++) {
        console.log(matriz[i][j]);
    }
}
```

### 2. Somando Elementos de uma Linha ou Coluna

```js
// Soma dos elementos da primeira linha
let somaLinha = 0;
for (let j = 0; j < matriz[0].length; j++) {
    somaLinha += matriz[0][j];
}
console.log(somaLinha);
```

### 3. Buscando um Elemento

```js
let encontrado = false;
for (let i = 0; i < matriz.length; i++) {
    for (let j = 0; j < matriz[i].length; j++) {
        if (matriz[i][j] === 5) {
            encontrado = true;
            break;
        }
    }
}
console.log(encontrado ? "Encontrado!" : "Não encontrado.");
```

---

## Desafios com Matrizes

- **Jogo da Velha:** Que tal criar um jogo da velha usando uma matriz 3x3?
- **Imagem em Preto e Branco:** Imagine uma matriz onde 0 é branco e 1 é preto. Você pode desenhar imagens simples!
- **Tabela de Notas:** Armazene as notas de vários alunos em várias matérias.

Se quiser se aprofundar em algum desses desafios, acesse as pastas específicas:

- [Jogo da Velha](./jogo-da-velha/README.md)
- [Manipulação de Imagens](./imagens/README.md)
- [Tabelas Dinâmicas](./tabelas/README.md)

---

## Dicas para Não Se Perder

- Sempre use dois loops para percorrer matrizes.
- Cuidado com os índices! Eles começam do zero.
- Teste seus códigos com matrizes pequenas antes de aumentar o tamanho.

---

## O que entendi?

> Escreva aqui, com suas próprias palavras, o que você aprendeu sobre matrizes avançadas. O que achou mais legal? Teve alguma dificuldade? Como você acha que pode usar matrizes no seu dia a dia?
