# Filtros em Matrizes: Buscando Dados como um Pro

Bem-vindo(a) à aula de **Filtros em Matrizes**!

Aqui, você vai aprender a encontrar exatamente o que procura em tabelas multidimensionais (matrizes), usando filtros avançados.

Preparado(a) para se tornar um(a) verdadeiro(a) detetive dos dados? Então, bora lá!

---

## Por que Filtrar Dados em Matrizes?

Imagine uma tabela gigante com notas de alunos, vendas de uma loja ou resultados de jogos.

Às vezes, você só quer ver os alunos que passaram, os produtos mais vendidos ou os jogos com mais gols.

É aí que entram os **filtros**: eles te ajudam a encontrar rapidamente as informações que realmente importam.

---

## Como Funciona um Filtro em Matrizes?

Filtrar uma matriz significa **percorrer todas as linhas e colunas** e selecionar apenas os dados que atendem a um critério específico.

Por exemplo:

- Mostrar só os alunos com nota maior que 7.
- Listar apenas os produtos com estoque baixo.
- Encontrar partidas com mais de 3 gols.

---

## Exemplo Prático: Filtrando Alunos Aprovados

Vamos supor que temos a seguinte matriz de alunos e notas:

```javascript
const alunos = [
    ["Ana", 8.5],
    ["Bruno", 6.0],
    ["Carla", 9.0],
    ["Diego", 5.5]
];
```

Queremos filtrar só quem foi aprovado (nota >= 7):

```javascript
const aprovados = [];
for (let i = 0; i < alunos.length; i++) {
    if (alunos[i][1] >= 7) {
        aprovados.push(alunos[i]);
    }
}
console.log(aprovados);
// Resultado: [["Ana", 8.5], ["Carla", 9.0]]
```

---

## Filtros Combinados: Indo Além

Você pode criar filtros ainda mais poderosos, combinando condições.

Por exemplo, alunos aprovados **e** com nome começando com "C":

```javascript
const aprovadosC = [];
for (let i = 0; i < alunos.length; i++) {
    if (alunos[i][1] >= 7 && alunos[i][0][0] === "C") {
        aprovadosC.push(alunos[i]);
    }
}
console.log(aprovadosC);
// Resultado: [["Carla", 9.0]]
```

---

## Desafio: Crie Seu Próprio Filtro

Tente criar um filtro para encontrar:

- Produtos com preço acima de R$ 100.
- Jogos em que o time da casa marcou mais gols que o visitante.
- Alunos com nota entre 6 e 8.

Use a criatividade! Se quiser se aprofundar, confira a pasta [`/filtros/avancados`](./avancados/README.md) para exemplos mais complexos.

---

## O que entendi?

> Escreva aqui, com suas próprias palavras, o que você aprendeu sobre filtros em matrizes. Como você usaria isso no seu dia a dia? Qual filtro você acha mais útil?
