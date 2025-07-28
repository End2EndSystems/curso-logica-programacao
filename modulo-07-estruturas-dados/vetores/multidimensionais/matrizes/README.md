# Matrizes (Vetores Multidimensionais)

Bem-vindo(a) à aula sobre **matrizes**!

Se você já entendeu vetores (listas), agora vai dar um passo além: vamos trabalhar com tabelas, ou seja, **vetores dentro de vetores**.

Preparado(a)? Bora lá!

---

## O que são Matrizes?

Imagine uma tabela do Excel, com linhas e colunas.

Cada célula dessa tabela pode guardar um valor.

Em programação, chamamos isso de **matriz** ou **vetor multidimensional**.

- **Vetor:** Uma lista simples, só com uma linha.
- **Matriz:** Uma tabela, com várias linhas e colunas.

Exemplo visual:

```plaintext
[ [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9] ]
```

Aqui temos uma matriz 3x3 (3 linhas e 3 colunas).

---

## Como Criar Matrizes

Em várias linguagens, você pode criar matrizes assim:

### Criando matrizes com JavaScript

```js
let matriz = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
];
```

### Criando matrizes com Python

```python
matriz = [
        [1, 2, 3],
        [4, 5, 6],
        [7, 8, 9]
]
```

---

## Acessando Elementos

Para acessar um elemento, você precisa informar a linha e a coluna:

- **JavaScript:** `matriz[linha][coluna]`
- **Python:** `matriz[linha][coluna]`

Exemplo: Para acessar o número 5 (segunda linha, segunda coluna):

```js
console.log(matriz[1][1]); // Saída: 5
```

```python
print(matriz[1][1]) # Saída: 5
```

---

## Percorrendo Matrizes

Para passar por todos os elementos, usamos dois loops (um dentro do outro):

### Percorrendo uma matriz com JavaScript

```js
for (let i = 0; i < matriz.length; i++) {
    for (let j = 0; j < matriz[i].length; j++) {
        console.log(matriz[i][j]);
    }
}
```

### Percorrendo uma matriz com Python

```python
for i in range(len(matriz)):
        for j in range(len(matriz[i])):
                print(matriz[i][j])
```

---

## Para que servem Matrizes?

- Jogos (tabuleiros, mapas)
- Imagens (cada pixel é um número)
- Tabelas de dados
- Qualquer situação que envolva linhas e colunas!

---

## Desafios para Praticar

1. Crie uma matriz 3x3 e preencha com números de 1 a 9.
2. Some todos os elementos da matriz.
3. Mostre apenas os elementos da diagonal principal.

---

## Explorando Mais

Se quiser se aprofundar, veja o conteúdo extra em [`/matrizes/avancado/README.md`](./avancado/README.md) sobre matrizes maiores, matrizes tridimensionais e aplicações reais.

---

## O que entendi?

> Escreva aqui, com suas palavras, o que você entendeu sobre matrizes. Dê exemplos, faça perguntas, ou anote dúvidas para discutir depois!
