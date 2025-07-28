# Fila de Prioridade

Bem-vindo à aula sobre **Filas de Prioridade**!

Aqui, vamos entender como organizar tarefas ou elementos de acordo com a sua importância, e não apenas pela ordem de chegada.

Preparado para dominar mais uma estrutura de dados essencial?

---

## O que é uma Fila de Prioridade?

Imagine que você está em uma fila para comprar ingressos, mas algumas pessoas têm prioridade (idosos, gestantes, etc).

Na programação, a **Fila de Prioridade** funciona assim: cada elemento tem uma prioridade, e quem tem a maior prioridade é atendido primeiro.

- **Fila comum:** ordem de chegada.
- **Fila de prioridade:** ordem de importância.

---

## Como funciona uma Fila de Prioridade?

Cada elemento da fila tem um valor de prioridade.

Quando você adiciona (enqueue) um novo elemento, ele é colocado na posição correta, de acordo com sua prioridade.

### Exemplo prático

| Elemento | Prioridade |
|----------|------------|
| Tarefa A |     2      |
| Tarefa B |     5      |
| Tarefa C |     1      |

Se você pedir para remover (dequeue) um elemento, a **Tarefa B** sai primeiro, pois tem prioridade 5 (quanto maior, mais importante).

---

## Onde usamos Filas de Prioridade?

- **Jogos:** para decidir qual personagem age primeiro.
- **Sistemas operacionais:** para gerenciar tarefas do computador.
- **Atendimentos:** hospitais, bancos, etc.

---

## Implementando uma Fila de Prioridade

Você pode implementar uma fila de prioridade de várias formas, mas a mais comum é usando uma **lista ordenada** ou uma **heap** (estrutura especial de árvore).

### Exemplo simples em JavaScript

```js
class FilaPrioridade {
    constructor() {
        this.itens = [];
    }

    enqueue(elemento, prioridade) {
        const novoItem = { elemento, prioridade };
        let adicionado = false;

        for (let i = 0; i < this.itens.length; i++) {
            if (prioridade > this.itens[i].prioridade) {
                this.itens.splice(i, 0, novoItem);
                adicionado = true;
                break;
            }
        }

        if (!adicionado) {
            this.itens.push(novoItem);
        }
    }

    dequeue() {
        return this.itens.shift();
    }
}
```

---

## Explorando mais: Heap

Se quiser se aprofundar, confira a pasta [`heap/`](./heap/README.md) para entender como essa estrutura pode deixar sua fila de prioridade ainda mais eficiente!

---

## Exercícios

1. Implemente uma fila de prioridade para organizar tarefas de um dia de estudos.
2. Modifique o exemplo acima para que a menor prioridade seja atendida primeiro.
3. Pesquise onde mais filas de prioridade são usadas no mundo real.

---

## O que entendi?

> Escreva aqui, com suas próprias palavras, o que você entendeu sobre filas de prioridade. Dê exemplos do seu dia a dia onde isso pode ser útil!
