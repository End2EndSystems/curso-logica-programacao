# Operações com Matrizes em JavaScript

Bem-vindo(a) à aula sobre **operações com matrizes**!

Aqui, vamos explorar como manipular tabelas (matrizes) em JavaScript, indo além do básico.

Prepare-se para entender como somar, multiplicar, inverter e até buscar dados em tabelas, tudo de um jeito prático e divertido!

---

## O que é uma Matriz?

Uma **matriz** é como uma tabela: linhas e colunas cheias de dados. Em JavaScript, usamos arrays dentro de arrays para criar matrizes. Por exemplo:

```js
const matriz = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
];
```

---

## Operações Básicas

### 1. Acessando Elementos

Para acessar um valor, usamos dois índices: `[linha][coluna]`.

```js
console.log(matriz[1][2]); // Mostra 6
```

### 2. Alterando Valores

```js
matriz[0][1] = 99; // Agora o valor na linha 0, coluna 1 é 99
```

---

## Operações Avançadas

### 1. Somando Todos os Elementos

```js
let soma = 0;
for (let i = 0; i < matriz.length; i++) {
    for (let j = 0; j < matriz[i].length; j++) {
        soma += matriz[i][j];
    }
}
console.log(soma);
```

### 2. Multiplicando Matrizes

Multiplicar matrizes é um pouco mais avançado.

Se quiser se aprofundar, veja o arquivo [`multiplicacao/README.md`](./multiplicacao/README.md).

### 3. Transpondo uma Matriz

Transpor é trocar linhas por colunas.

```js
function transpor(m) {
    const resultado = [];
    for (let i = 0; i < m[0].length; i++) {
        resultado[i] = [];
        for (let j = 0; j < m.length; j++) {
            resultado[i][j] = m[j][i];
        }
    }
    return resultado;
}
```

---

## Explorando Mais

- [Multiplicação de Matrizes](./multiplicacao/README.md)
- [Busca em Matrizes](./busca/README.md)
- [Matrizes Dinâmicas](./dinamicas/README.md)

---

## Dicas para Não Se Perder

- Sempre confira os índices!
- Use `console.log` para ver como a matriz está em cada passo.
- Teste com matrizes pequenas antes de partir para tabelas grandes.

---

## O que entendi?

> Escreva aqui, com suas palavras, o que você aprendeu sobre operações com matrizes. O que achou mais fácil? O que achou mais difícil? Tem alguma dúvida? Anote tudo aqui!
