# Matrizes Avançado: Tabelas em Programação

## Introdução

Chegou a hora de dar um passo além!

Você já aprendeu sobre vetores e matrizes, mas agora vamos explorar como as matrizes podem ser usadas para criar **tabelas** em programação.

Sabe aquelas tabelas que você vê em planilhas ou sites? Vamos aprender a representá-las e manipulá-las com código!

---

## O que é uma Tabela?

Uma tabela nada mais é do que uma matriz: linhas e colunas organizadas para guardar informações.

Por exemplo, imagine uma tabela de notas dos alunos:

| Nome     | Matemática | Português | Ciências |
|----------|------------|-----------|----------|
| Ana      | 8          | 7         | 9        |
| Bruno    | 6          | 8         | 7        |
| Camila   | 9          | 6         | 8        |

No código, isso pode ser representado por uma matriz bidimensional.

---

## Como Representar Tabelas com Matrizes

Em muitas linguagens, usamos arrays (ou listas) dentro de arrays para criar tabelas.

Veja um exemplo em JavaScript:

```js
const tabelaNotas = [
    ["Ana", 8, 7, 9],
    ["Bruno", 6, 8, 7],
    ["Camila", 9, 6, 8]
];
```

Cada linha é um aluno, cada coluna é uma matéria.

---

## Acessando e Modificando Dados

Para acessar ou modificar um valor, usamos dois índices: o da linha e o da coluna.

```js
// Nota de Ciências da Camila
console.log(tabelaNotas[2][3]); // 8

// Alterando a nota de Português do Bruno para 9
tabelaNotas[1][2] = 9;
```

---

## Percorrendo Tabelas

Para mostrar todos os dados, usamos dois loops (um dentro do outro):

```js
for (let i = 0; i < tabelaNotas.length; i++) {
    for (let j = 0; j < tabelaNotas[i].length; j++) {
        console.log(tabelaNotas[i][j]);
    }
}
```

---

## Desafios Comuns

- **Tamanho Variável:** Nem sempre todas as linhas têm o mesmo tamanho.
- **Busca de Dados:** Como encontrar um aluno específico?
- **Atualização em Massa:** Como atualizar todas as notas de uma matéria?

Esses desafios são comuns em sistemas reais!

---

## Exercício Prático

Monte uma tabela de notas para 5 alunos e 4 matérias. Depois, escreva um código que calcule a média de cada aluno e mostre quem teve a maior média.

---

## Indo Mais Fundo

Se quiser se aprofundar, veja a pasta [`operacoes/README.md`](./operacoes/README.md) para aprender sobre operações avançadas com tabelas, como ordenação e filtragem!

---

## O que entendi?

> Escreva aqui, com suas palavras, o que você entendeu sobre tabelas em programação, como elas funcionam e para que servem. Se ficou alguma dúvida, anote também!
