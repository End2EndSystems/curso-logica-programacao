# Módulo 07: Estruturas de Dados - Listas

---

## O que são Listas?

Imagina que você tem uma caixa onde pode guardar vários itens, como cartas de Pokémon, figurinhas ou até mesmo suas músicas favoritas.

Em programação, essa caixa se chama **lista**!

Uma lista é uma estrutura de dados que permite guardar vários valores em uma única variável, organizados em uma ordem específica.

---

## Por que usar Listas?

- Guardar vários dados juntos (ex: nomes de amigos, notas das provas, etc.)
- Acessar, modificar ou remover itens facilmente
- Organizar informações para facilitar buscas e operações

---

## Como criar uma Lista?

Em Python, por exemplo, criar uma lista é super simples:

```python
# Lista de frutas
frutas = ["maçã", "banana", "laranja"]
```

Você pode colocar qualquer tipo de dado em uma lista: números, textos, ou até outras listas!

---

## Acessando Elementos

Cada item da lista tem uma posição (índice), começando do zero:

```python
print(frutas[0])  # Vai mostrar 'maçã'
print(frutas[2])  # Vai mostrar 'laranja'
```

---

## Modificando Listas

Adicionar, remover ou mudar itens é fácil:

```python
frutas.append("uva")      # Adiciona 'uva' no final
frutas.remove("banana")   # Remove 'banana'
frutas[1] = "melancia"    # Troca 'laranja' por 'melancia'
```

---

## Percorrendo uma Lista

Quer mostrar todos os itens? Use um laço:

```python
for fruta in frutas:
    print(fruta)
```

---

## Listas dentro de Listas

Sim, é possível! Isso se chama **lista multidimensional** (ou matriz):

```python
tabuleiro = [
    ["X", "O", "X"],
    ["O", "X", "O"],
    ["O", "X", "X"]
]
```

---

## Desafios para Praticar

1. Crie uma lista com seus filmes favoritos e mostre cada um deles.
2. Peça para o usuário digitar 5 números, guarde em uma lista e mostre a soma.
3. Crie uma lista de compras e permita adicionar e remover itens.

---

## Indo Mais Fundo

Quer saber mais sobre listas? Veja os tópicos abaixo:

- [Listas em Python: Métodos e Operações](./listas-python/README.md)
- [Listas Multidimensionais (Matrizes)](../vetores/multidimensionais/matrizes/README.md)

---

## O que entendi?

> Escreva aqui, com suas palavras, o que você entendeu sobre listas. Pode ser um resumo, exemplos que você inventou, ou até dúvidas que ficaram!
