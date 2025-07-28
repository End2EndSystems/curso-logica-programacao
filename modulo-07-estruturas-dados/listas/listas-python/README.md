# Módulo 07: Estruturas de Dados — Listas em Python

## Introdução

Você já tentou guardar vários dados de uma vez só? Tipo, as notas de todos os seus amigos, ou os nomes dos seus jogos favoritos? Fazer isso usando só variáveis seria um caos! É aí que entram as **listas** em Python. Elas são como caixas mágicas onde você pode guardar vários itens, acessar qualquer um deles rapidinho e até mudar a ordem se quiser.

---

## O que são listas?

Uma **lista** é uma estrutura de dados que armazena uma sequência de elementos. Em Python, listas são super flexíveis: podem guardar números, textos, ou até outras listas!

```python
# Exemplo de lista
notas = [8.5, 7.0, 9.2, 6.8]
nomes = ["Ana", "Bruno", "Carlos"]
misturada = [1, "texto", True, 3.14]
```

---

## Como criar listas

Você cria uma lista usando colchetes `[]` e separando os itens por vírgula.

```python
frutas = ["maçã", "banana", "laranja"]
```

### Lista vazia

```python
vazia = []
```

---

## Acessando elementos

Cada item da lista tem uma posição (índice), começando do zero.

```python
print(frutas[0])  # maçã
print(frutas[2])  # laranja
```

### Índices negativos

Você pode usar índices negativos para acessar do final para o começo.

```python
print(frutas[-1])  # laranja
```

---

## Modificando listas

### Alterando valores

```python
frutas[1] = "uva"
print(frutas)  # ['maçã', 'uva', 'laranja']
```

### Adicionando elementos

- `append()`: adiciona no final
- `insert()`: adiciona em qualquer posição

```python
frutas.append("melancia")
frutas.insert(1, "abacaxi")
```

### Removendo elementos

- `remove()`: remove pelo valor
- `pop()`: remove pelo índice

```python
frutas.remove("uva")
frutas.pop(0)  # remove o primeiro
```

---

## Percorrendo listas

Você pode usar um `for` para passar por cada item:

```python
for fruta in frutas:
    print(fruta)
```

---

## Funções úteis para listas

- `len(lista)`: quantidade de itens
- `sum(lista)`: soma dos itens (se forem números)
- `max(lista)`, `min(lista)`: maior e menor valor

```python
notas = [8.5, 7.0, 9.2, 6.8]
print(len(notas))  # 4
print(sum(notas))  # 31.5
print(max(notas))  # 9.2
```

---

## Listas dentro de listas

Você pode ter listas dentro de listas (listas 2D):

```python
matriz = [
    [1, 2, 3],
    [4, 5, 6]
]
print(matriz[1][2])  # 6
```

---

## Desafios para praticar

1. Crie uma lista com os nomes dos seus amigos e imprima cada nome.
2. Some todas as notas de uma lista e calcule a média.
3. Crie uma lista de compras e permita que o usuário adicione e remova itens.
4. Repita os exercícios utilizando outra linguagem de programação como javascript ou c#. (adicione cada um em sua respectiva pasta como listas-js e listas-csharp).

---

## O que entendi?

> Escreva aqui, com suas palavras, o que você entendeu sobre listas em Python. O que achou mais fácil? O que ainda ficou confuso?
