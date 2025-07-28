# Módulo 07: Estruturas de Dados — Pilhas

---

## O que são Pilhas?

Imagine uma pilha de pratos: você só consegue pegar o prato que está no topo. Assim funciona a estrutura de dados chamada **pilha**. Ela segue a regra **LIFO** (*Last In, First Out*), ou seja, o último elemento a entrar é o primeiro a sair.

---

## Para que servem Pilhas?

Pilhas são usadas em várias situações, como:

- Desfazer ações em editores de texto (Ctrl+Z)
- Navegação entre páginas (voltar e avançar no navegador)
- Avaliação de expressões matemáticas
- Controle de chamadas de funções em programação

---

## Como funciona uma Pilha?

As principais operações de uma pilha são:

- **push**: adiciona um elemento no topo da pilha
- **pop**: remove o elemento do topo da pilha
- **peek** (ou **top**): olha qual elemento está no topo, sem remover
- **isEmpty**: verifica se a pilha está vazia

```python
# Exemplo simples de pilha em Python
pilha = []

# Adicionando elementos
pilha.append(1)  # push
pilha.append(2)
pilha.append(3)

print(pilha)  # [1, 2, 3]

# Removendo o topo
topo = pilha.pop()  # pop
print(topo)  # 3
print(pilha)  # [1, 2]
```

---

## Visualizando a Pilha

```plaintext
Topo -> [3]
         [2]
Base -> [1]
```

Quando você faz um `pop`, o 3 sai primeiro. Se fizer outro `pop`, sai o 2, e assim por diante.

---

## Desafios para praticar

1. Implemente uma pilha usando listas em Python.
2. Crie um programa que leia uma palavra e use uma pilha para verificar se ela é um palíndromo.
3. Simule o funcionamento do botão "voltar" de um navegador usando pilhas.

---

## Explorando mais

Se quiser se aprofundar, veja a pasta [`exemplos`](./exemplos/README.md) com códigos comentados e desafios extras.

---

## O que entendi?

> Escreva aqui, com suas palavras, o que você entendeu sobre pilhas. Como você explicaria para um amigo? Qual exemplo mais te chamou atenção?
