# Módulo 07: Estruturas de Dados - Vetores

Bem-vindo(a) a mais uma etapa da sua jornada na programação!

Aqui, vamos explorar um dos conceitos mais importantes e usados em qualquer linguagem: **vetores** (ou arrays).

Prepare-se para entender como guardar e manipular vários dados de uma vez só, de um jeito super prático!

---

## O que são Vetores?

Imagine que você tem uma caixa de lápis de cor.

Cada lápis tem uma cor diferente e está em uma posição específica na caixa.

Um **vetor** funciona mais ou menos assim: é uma estrutura que guarda vários valores, cada um em uma posição (índice).

> **Nota sobre índices:**  
> Em muitas linguagens de programação, como JavaScript e Python, os índices dos vetores começam em **0**.
>/
> Isso acontece por questões históricas e de eficiência: internamente, o índice representa um deslocamento a partir do início do vetor.
>/
> Assim, o primeiro elemento está na posição 0, o segundo na posição 1, e assim por diante.
>/
> Porém, algumas linguagens, como **Delphi** ou **Lua**, podem começar os índices em **1**.
>/
> Por isso, sempre confira como a linguagem que você está usando trata os índices dos vetores!

- **Exemplo:**

    ```js
    let cores = ["vermelho", "azul", "verde"];
    // Índices:     0         1        2
    ```

Você pode acessar qualquer cor usando o índice dela:

```js
console.log(cores[1]); // azul
```

---

## Por que usar Vetores?

- Guardar vários dados do mesmo tipo juntos.
- Facilitar buscas, ordenações e manipulações.
- Deixar o código mais organizado e eficiente.

---

## Como criar um Vetor?

### Em JavaScript

```js
let numeros = [10, 20, 30, 40, 50];
```

### Em Python

```python
numeros = [10, 20, 30, 40, 50]
```

Você pode acessar, modificar e até adicionar novos valores!

---

## Acessando e Modificando Elementos

- **Acessar:**

    ```js
    let primeiro = numeros[0]; // 10
    ```

- **Modificar:**  

    ```js
    numeros[2] = 99; // Agora o vetor é [10, 20, 99, 40, 50]
    ```

---

## Percorrendo um Vetor

Geralmente usamos loops para trabalhar com todos os elementos:

```js
for (let i = 0; i < numeros.length; i++) {
    console.log(numeros[i]);
}
```

---

## Desafios Comuns

- **Índices começam do zero!**
- Cuidado para não acessar posições que não existem.
- Vetores podem ser de qualquer tipo: números, textos, até outros vetores!

---

## Explorando Mais

Se quiser se aprofundar, confira:

- [Vetores Multidimensionais](./multidimensionais/README.md)
- [Métodos úteis de vetores](./metodos/README.md)

---

## O que entendi?

> Escreva aqui, com suas próprias palavras, o que você entendeu sobre vetores. Dê exemplos, explique para você mesmo(a) como se estivesse ensinando alguém!

---

Pronto para praticar? Bora codar!
