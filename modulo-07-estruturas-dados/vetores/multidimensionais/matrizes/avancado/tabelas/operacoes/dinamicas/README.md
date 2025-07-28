# Matrizes Dinâmicas: Operações em Tabelas

Bem-vindo(a) a mais uma etapa da nossa jornada com matrizes!

Agora vamos explorar como trabalhar com **tabelas dinâmicas** em programação, ou seja, como criar, modificar e manipular matrizes que podem crescer ou diminuir conforme a necessidade do seu programa.

## O que são Matrizes Dinâmicas?

Até agora, trabalhamos com matrizes de tamanho fixo, onde você já sabia quantas linhas e colunas teria.

Mas e se você não souber quantos dados vai precisar guardar?

É aí que entram as **matrizes dinâmicas**!

Elas permitem adicionar ou remover linhas e colunas enquanto o programa está rodando.

Imagine uma planilha do Excel onde você pode adicionar novas linhas de notas de alunos a qualquer momento.

É exatamente isso que vamos aprender a fazer!

## Por que usar Matrizes Dinâmicas?

- **Flexibilidade:** Você não precisa saber o tamanho da matriz antes de começar.
- **Eficiência:** Só usa memória para o que realmente precisa.
- **Facilidade:** Fica mais fácil lidar com dados que mudam de tamanho, como listas de compras, tabelas de jogos, ou registros de alunos.

## Como Criar Matrizes Dinâmicas

Em muitas linguagens, como Python, você pode usar listas dentro de listas para criar matrizes dinâmicas. Veja um exemplo:

```python
# Criando uma matriz dinâmica vazia
tabela = []

# Adicionando linhas dinamicamente
tabela.append([10, 20, 30])
tabela.append([40, 50, 60])

print(tabela)
# Saída: [[10, 20, 30], [40, 50, 60]]
```

Você pode adicionar quantas linhas quiser, e cada linha pode ter quantas colunas precisar!

## Operações Básicas em Matrizes Dinâmicas

### 1. Adicionar uma nova linha

```python
nova_linha = [70, 80, 90]
tabela.append(nova_linha)
```

### 2. Adicionar uma nova coluna

Para adicionar uma coluna, você precisa adicionar um novo elemento em cada linha:

```python
for linha in tabela:
    linha.append(100)
```

### 3. Remover uma linha

```python
tabela.pop(1)  # Remove a segunda linha
```

### 4. Remover uma coluna

```python
for linha in tabela:
    linha.pop(0)  # Remove a primeira coluna de cada linha
```

## Desafios para Praticar

1. Crie uma matriz dinâmica para guardar as notas de vários alunos em diferentes matérias.
2. Adicione e remova linhas e colunas conforme novos alunos entram ou saem.
3. Mostre a matriz final na tela.

## Explorando Mais

Se quiser se aprofundar, confira a pasta [`/dinamicas/extras`](./extras/README.md) para exemplos avançados, como matrizes irregulares (onde cada linha pode ter um número diferente de colunas) e dicas de performance!

## O que entendi?

> Escreva aqui, com suas próprias palavras, o que você aprendeu sobre matrizes dinâmicas, para fixar o conteúdo e tirar suas dúvidas!
