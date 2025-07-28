# Filtros Avançados em Matrizes

Bem-vindo(a) a mais uma aula do nosso curso de lógica de programação!

Hoje vamos explorar como fazer **buscas avançadas** em matrizes usando **filtros**.

Se você já achou legal buscar um valor em uma matriz, prepare-se: agora vamos aprender a encontrar exatamente o que queremos, mesmo em tabelas grandes e complexas!

---

## Por que usar filtros avançados?

Imagine que você tem uma tabela com notas de alunos em várias matérias.

E se quiser encontrar todos os alunos que tiraram nota acima de 8 em Matemática **e** estão na turma B?

Só buscar por um valor não resolve, né? É aí que entram os **filtros avançados**!

---

## Como funcionam os filtros em matrizes?

Filtros são condições que usamos para selecionar apenas os dados que nos interessam.

Em programação, isso significa percorrer a matriz e verificar se cada elemento (ou linha) atende aos critérios que definimos.

### Exemplo de matriz de alunos

```markdown
| Nome    | Turma | Matemática | Português |
|---------|-------|------------|-----------|
| Ana     | A     | 9          | 7         |
| Bruno   | B     | 8          | 8         |
| Carla   | B     | 10         | 9         |
| Daniel  | A     | 7          | 6         |
| Elisa   | B     | 9          | 10        |
```

### Filtro: alunos da turma B com nota de Matemática maior que 8

Para encontrar esses alunos, precisamos:

1. Percorrer cada linha da matriz.
2. Verificar se a turma é "B".
3. Verificar se a nota de Matemática é maior que 8.
4. Se sim, guardar ou mostrar essa linha.

---

## Implementando filtros avançados

Vamos ver como isso ficaria em pseudocódigo:

```pseudo
para cada aluno na matriz:
    se aluno["Turma"] == "B" e aluno["Matemática"] > 8:
        mostrar aluno
```

Em Python, por exemplo:

```python
alunos = [
    ["Ana", "A", 9, 7],
    ["Bruno", "B", 8, 8],
    ["Carla", "B", 10, 9],
    ["Daniel", "A", 7, 6],
    ["Elisa", "B", 9, 10]
]

for aluno in alunos:
    nome, turma, matematica, portugues = aluno
    if turma == "B" and matematica > 8:
        print(aluno)
```

---

## Filtros combinados e múltiplos critérios

Você pode combinar quantos filtros quiser!

Por exemplo:

- Alunos da turma A **ou** B com nota de Português acima de 8.
- Alunos com nota de Matemática **entre** 8 e 10.

Essas combinações deixam suas buscas muito mais poderosas!

---

## Explorando mais: Filtros dinâmicos

Se quiser se aprofundar, veja a aula extra em [`filtros/dinamicos/README.md`](../dinamicos/README.md) para aprender como criar filtros que o usuário pode escolher na hora!

---

## O que entendi?

> Escreva aqui, com suas próprias palavras, o que você aprendeu sobre filtros avançados em matrizes. Como você usaria isso em um projeto seu? Quais dúvidas ainda ficaram?
