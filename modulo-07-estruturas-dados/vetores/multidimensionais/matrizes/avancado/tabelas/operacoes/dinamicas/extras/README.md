# Matrizes Dinâmicas: Operações Extras

Bem-vindo(a) a mais uma etapa do nosso curso de lógica de programação!

Aqui, vamos explorar operações extras com **matrizes dinâmicas**.

Se você já entendeu como criar, acessar e modificar matrizes, está pronto para ir além e descobrir como manipular esses dados de formas ainda mais poderosas.

---

## O que são Matrizes Dinâmicas?

Diferente das matrizes fixas, as **matrizes dinâmicas** podem crescer ou diminuir durante a execução do programa.

Isso é super útil quando não sabemos de antemão quantos dados vamos precisar armazenar.

**Exemplo em JavaScript:**

```js
let matriz = [
    [1, 2],
    [3, 4]
];

// Adicionando uma nova linha
matriz.push([5, 6]);

// Adicionando um novo elemento em uma linha existente
matriz[0].push(7);
```

---

## Operações Extras com Matrizes Dinâmicas

Vamos ver algumas operações que vão deixar seu código muito mais flexível e poderoso!

### 1. Adicionar e Remover Linhas

- **Adicionar:** Use `push()` para adicionar uma nova linha (um novo array).
- **Remover:** Use `pop()` para remover a última linha.

```js
matriz.push([7, 8]); // adiciona nova linha
matriz.pop();        // remove a última linha
```

### 2. Adicionar e Remover Colunas

- **Adicionar:** Use `push()` em uma linha específica.
- **Remover:** Use `pop()` em uma linha específica.

```js
matriz[1].push(9); // adiciona nova coluna na linha 1
matriz[1].pop();   // remove a última coluna da linha 1
```

### 3. Percorrer Matrizes Dinâmicas

Você pode usar dois loops para acessar todos os elementos:

```js
for (let i = 0; i < matriz.length; i++) {
    for (let j = 0; j < matriz[i].length; j++) {
        console.log(matriz[i][j]);
    }
}
```

### 4. Encontrar Elementos

Procure por um valor específico em toda a matriz:

```js
function encontrarValor(matriz, valor) {
    for (let i = 0; i < matriz.length; i++) {
        for (let j = 0; j < matriz[i].length; j++) {
            if (matriz[i][j] === valor) {
                return [i, j];
            }
        }
    }
    return null;
}
```

---

## Desafios para Praticar

1. Crie uma matriz dinâmica e adicione 3 linhas com 4 colunas cada.
2. Remova a segunda linha da matriz.
3. Adicione um novo elemento na terceira coluna da primeira linha.
4. Escreva uma função que some todos os elementos da matriz.

---

## Explorando Mais

Se quiser se aprofundar, confira a pasta [`/extras/explicacoes`](./explicacoes/README.md) para entender como funcionam as matrizes dinâmicas em outras linguagens como Python e Java.

---

## O que entendi?

> Escreva aqui, com suas próprias palavras, o que você aprendeu sobre operações extras com matrizes dinâmicas. O que achou mais interessante? Teve alguma dificuldade? Como você usaria isso em um projeto seu?
