# Filtros Dinâmicos em Matrizes: Explicação

## Introdução

Você já imaginou como os aplicativos conseguem mostrar só o que você procura, como filmes de ação na Netflix ou apenas seus amigos online no Instagram?

Isso é possível graças aos **filtros dinâmicos**!

Hoje, vamos entender como aplicar filtros em matrizes (ou tabelas) para encontrar exatamente o que queremos.

---

## O que são Filtros Dinâmicos?

Filtros dinâmicos são formas de buscar e exibir apenas os dados que atendem a certos critérios, sem precisar mexer na estrutura da matriz.

Eles deixam a busca mais rápida, organizada e personalizada.

Por exemplo:

Imagine uma tabela com notas de alunos.

Se você quiser ver só quem tirou acima de 8, pode usar um filtro dinâmico para mostrar só esses alunos.

---

## Como Funcionam os Filtros Dinâmicos?

1. **Defina o critério:** O que você quer buscar? (Ex: notas acima de 8)
2. **Percorra a matriz:** Olhe cada linha/coluna da tabela.
3. **Verifique o critério:** Se o dado atende ao critério, ele entra no resultado.
4. **Monte o resultado:** Crie uma nova matriz/tabela só com os dados filtrados.

---

## Exemplo Prático

Vamos supor que temos a seguinte matriz de alunos e notas:

```markdown
| Nome   | Nota |
|--------|------|
| Ana    | 7.5  |
| Bruno  | 9.0  |
| Carla  | 8.2  |
| Diego  | 6.8  |
| Elisa  | 9.5  |
```

Se quisermos filtrar só quem tirou nota maior que 8:

```markdown
| Nome   | Nota |
|--------|------|
| Bruno  | 9.0  |
| Carla  | 8.2  |
| Elisa  | 9.5  |
```

---

## Por que usar Filtros Dinâmicos?

- **Rapidez:** Encontre o que precisa sem perder tempo.
- **Organização:** Deixa a tabela mais limpa.
- **Personalização:** Você escolhe o que quer ver.

---

## Desafio

Tente criar um filtro para mostrar apenas os alunos com nota menor que 7. O que muda no seu código ou lógica?

---

## Indo Mais Fundo

Se quiser entender como criar filtros mais avançados (como combinar vários critérios ou filtrar por texto), confira a pasta `filtros/avancado/README.md` para exemplos e exercícios extras!

---

## O que entendi?

> Escreva aqui, com suas palavras, o que você entendeu sobre filtros dinâmicos em matrizes. Como você usaria isso em um projeto seu?
