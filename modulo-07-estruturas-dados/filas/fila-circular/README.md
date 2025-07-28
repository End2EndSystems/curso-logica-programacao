# Fila Circular

## O que é uma Fila Circular?

Imagine uma fila normal, como a de um caixa de supermercado.

Agora, pense que, quando alguém sai da frente, o espaço vazio pode ser ocupado por quem chega no final, formando um círculo.

Isso é uma **fila circular**!

Ela é uma estrutura de dados onde o último elemento está conectado ao primeiro, aproveitando melhor o espaço disponível.

---

## Por que usar uma Fila Circular?

Em filas tradicionais, quando removemos elementos do início, o espaço fica inutilizado.

Com a fila circular, conseguimos reutilizar esse espaço, evitando desperdício de memória.

Isso é muito útil em situações como:

- Impressoras (gerenciando trabalhos de impressão)
- Sistemas operacionais (controle de tarefas)
- Jogos (rodízio de jogadores)

---

## Como funciona na prática?

A fila circular usa um array fixo e dois ponteiros:

- **Início (front):** indica onde está o primeiro elemento.
- **Fim (rear):** indica onde será inserido o próximo elemento.

Quando o fim chega ao final do array, ele volta para o início, formando o círculo!

### Exemplo visual

```plaintext
[ 3 ][ 5 ][ 7 ][   ][   ]
    ^           ^
 front        rear
```

Se inserirmos mais um elemento:

```plaintext
[ 3 ][ 5 ][ 7 ][ 9 ][   ]
    ^               ^
 front            rear
```

Se removermos um elemento:

```plaintext
[   ][ 5 ][ 7 ][ 9 ][   ]
          ^           ^
        front        rear
```

Se o rear chegar ao final, ele volta para o início do array!

---

## Implementação básica em pseudocódigo

```pseudo
inicializar fila com tamanho N
front = 0
rear = 0

ENFILEIRAR(elemento):
     se (fila cheia):
          erro "Fila cheia"
     fila[rear] = elemento
     rear = (rear + 1) % N

DESENFILEIRAR():
     se (fila vazia):
          erro "Fila vazia"
     elemento = fila[front]
     front = (front + 1) % N
     retorna elemento
```

---

## Desafios e dicas

- **Cuidado com o estouro!** Sempre use o operador `%` para garantir que os ponteiros voltem ao início do array.
- **Fila cheia ou vazia?** Uma dica é sempre deixar uma posição vazia para diferenciar fila cheia de fila vazia.

---

## Explorando mais

Se quiser se aprofundar, confira a pasta [`conceitos-fila-circular`](./conceitos-fila-circular/README.md) para entender detalhes como gerenciamento de ponteiros e aplicações reais.

---

## O que entendi?

> Escreva aqui, com suas palavras, o que você entendeu sobre filas circulares. Como você explicaria para um amigo? Quais dúvidas ainda ficaram?
