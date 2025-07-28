# Módulo 07: Estruturas de Dados - Filas

## O que são Filas?

Imagine uma fila no cinema ou na cantina da escola: quem chega primeiro, é atendido primeiro

Em programação, uma **fila** funciona exatamente assim!

É uma estrutura de dados onde o primeiro elemento a entrar é o primeiro a sair.

Por isso, chamamos de **FIFO** (First In, First Out).

---

## Por que usar Filas?

Filas são super úteis quando precisamos organizar tarefas ou dados em ordem de chegada.

Alguns exemplos do dia a dia:

- Impressoras: documentos são impressos na ordem em que foram enviados.
- Atendimento ao cliente: cada pessoa é atendida na ordem em que chegou.
- Jogos online: jogadores entram em partidas conforme a ordem de entrada.

---

## Como funciona uma Fila?

Uma fila tem duas operações principais:

- **Enfileirar (enqueue):** adicionar um elemento ao final da fila.
- **Desenfileirar (dequeue):** remover o elemento do início da fila.

Visualize assim:

```plaintext
[primeiro] -> [segundo] -> [terceiro] -> ...
    ^                              ^
    |                              |
  saída                        entrada
```

---

## Implementando uma Fila em JavaScript

Vamos criar uma fila simples usando um array:

```js
class Fila {
  constructor() {
     this.itens = [];
  }

  // Adiciona no final
  enfileirar(elemento) {
     this.itens.push(elemento);
  }

  // Remove do início
  desenfileirar() {
     if (this.estaVazia()) return undefined;
     return this.itens.shift();
  }

  // Verifica se está vazia
  estaVazia() {
     return this.itens.length === 0;
  }

  // Mostra o primeiro da fila
  frente() {
     return this.itens[0];
  }

  // Tamanho da fila
  tamanho() {
     return this.itens.length;
  }
}
```

Teste você mesmo!

```js
const fila = new Fila();
fila.enfileirar('Ana');
fila.enfileirar('Bruno');
console.log(fila.desenfileirar()); // Ana
console.log(fila.frente()); // Bruno
```

---

## Desafios para praticar

1. Crie uma fila de tarefas para um jogo: cada tarefa deve ser executada na ordem em que foi adicionada.
2. Simule uma fila de atendimento em uma lanchonete usando a classe acima.
3. O que acontece se tentar desenfileirar de uma fila vazia? Teste e explique.

---

## Indo mais fundo: Filas Circulares e Filas de Prioridade

Se quiser se aprofundar, explore:

- [Filas Circulares](./fila-circular/README.md): economizam espaço, reaproveitando posições já liberadas.
- [Filas de Prioridade](./fila-prioridade/README.md): elementos com maior prioridade saem antes, mesmo que tenham chegado depois.

---

## O que entendi?

> Escreva aqui, com suas palavras, o que você entendeu sobre filas. Dê exemplos do seu dia a dia ou crie um mini-resumo para revisar depois!
