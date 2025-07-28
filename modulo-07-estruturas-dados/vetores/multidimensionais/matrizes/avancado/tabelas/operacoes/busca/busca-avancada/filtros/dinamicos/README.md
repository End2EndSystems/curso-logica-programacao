# Filtros Dinâmicos em Matrizes

Bem-vindo(a) a mais uma aula do nosso curso de lógica de programação!

Hoje vamos explorar um tema super útil e interessante: **filtros dinâmicos em matrizes**.

Se você já curtiu trabalhar com vetores e matrizes, prepare-se para dar um passo além e aprender como buscar informações de forma flexível e poderosa!

---

## O que são Filtros Dinâmicos?

Filtros dinâmicos são técnicas que permitem buscar e selecionar dados em matrizes (ou tabelas) de acordo com critérios que podem mudar durante a execução do programa.

Ou seja, você pode pedir para o usuário escolher o que ele quer procurar, e o programa responde mostrando só o que interessa!

Imagine uma tabela de alunos com notas.

Com filtros dinâmicos, você pode buscar todos que tiraram nota acima de 8, ou só os que têm nome começando com "A", ou ainda combinar vários critérios!

---

## Por que usar Filtros Dinâmicos?

- **Flexibilidade:** O usuário pode escolher o que quer ver.
- **Eficiência:** Você não precisa criar vários códigos diferentes para cada busca.
- **Organização:** O código fica mais limpo e fácil de manter.

---

## Como funciona na prática?

Vamos supor que temos a seguinte matriz de alunos:

```javascript
const alunos = [
    ["Ana", 9.5, "Aprovado"],
    ["Bruno", 7.0, "Aprovado"],
    ["Carlos", 5.5, "Recuperação"],
    ["Diana", 8.0, "Aprovado"],
    ["Eduardo", 4.0, "Reprovado"]
];
```

Agora, queremos filtrar todos os alunos que foram "Aprovado". Veja como podemos fazer isso:

```javascript
const aprovados = alunos.filter(aluno => aluno[2] === "Aprovado");
console.table(aprovados);
```

E se quisermos buscar todos com nota maior que 8?

```javascript
const notaAlta = alunos.filter(aluno => aluno[1] > 8);
console.table(notaAlta);
```

---

## Tornando o Filtro Dinâmico

O legal é deixar o filtro dinâmico, ou seja, o usuário escolhe o critério! Por exemplo:

```javascript
function filtrarAlunos(criterio, valor) {
    return alunos.filter(aluno => aluno[criterio] === valor);
}

// Exemplo: filtrar por status
console.table(filtrarAlunos(2, "Aprovado"));
```

Você pode até pedir para o usuário digitar o critério e o valor pelo teclado!

---

## Explorando Mais

Se quiser se aprofundar, confira a pasta [`/filtros/dinamicos/explicacao`](./explicacao/README.md) para entender como criar filtros combinados (ex: nota > 7 **e** status "Aprovado") e como deixar seu código ainda mais flexível!

---

## Exercício Prático

1. Crie uma matriz com pelo menos 5 linhas e 3 colunas (ex: produtos, preços, estoque).
2. Implemente uma função que filtre os dados de acordo com um critério escolhido pelo usuário.
3. Mostre o resultado na tela.

---

## O que entendi?

> Escreva aqui, com suas próprias palavras, o que você entendeu sobre filtros dinâmicos em matrizes. Como você acha que pode usar isso em outros projetos? O que ficou mais fácil ou mais difícil para você?
