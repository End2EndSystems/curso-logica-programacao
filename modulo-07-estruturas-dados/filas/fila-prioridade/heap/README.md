# Heap: A Fila de Prioridade Turbinada 🚀

Você já pensou em como organizar uma fila onde alguns itens são mais importantes que outros?

E se, além disso, você pudesse garantir que sempre o item mais importante seja retirado rapidinho, sem perder tempo procurando?

É aí que entra o **Heap**!

## O que é um Heap?

Um **Heap** é uma estrutura de dados em forma de árvore (tipo uma pirâmide), onde cada elemento tem uma relação de prioridade com seus "filhos".

Existem dois tipos principais:

- **Max Heap**: O maior valor sempre fica no topo.
- **Min Heap**: O menor valor sempre fica no topo.

Assim, quando você precisa pegar o item mais importante (ou menos, dependendo do caso), ele está sempre ali, fácil de acessar!

## Como funciona na prática?

Imagina um jogo onde você precisa sempre atacar o inimigo mais forte primeiro.

Com um Heap, você sempre sabe quem é o mais forte, sem precisar olhar todos de novo.

Isso deixa sua fila de prioridade **super eficiente**!

### Operações principais

- **Inserir**: Adiciona um novo elemento e reorganiza a árvore para manter a ordem.
- **Remover**: Remove o elemento do topo (o mais importante) e reorganiza tudo rapidinho.
- **Espiar**: Dá uma olhada no topo sem remover.

Essas operações são feitas em tempo **logarítmico** (O(log n)), ou seja, mesmo com muitos elementos, tudo continua rápido!

### Visualizando um Heap

```plaintext
    10
       /  \
      7    8
     / \  /
    2  5 3
```

No exemplo acima, 10 é o maior valor (Max Heap), então ele fica no topo.

## Quando usar Heap?

- Fila de prioridade (como em jogos, sistemas operacionais, ou apps de entrega)
- Algoritmos de busca de menor caminho (tipo Dijkstra)
- Ordenação eficiente (Heap Sort)

---

## O que entendi?

> Escreva aqui, com suas palavras, o que você entendeu sobre Heap e como ele pode ajudar a deixar sua fila de prioridade mais rápida e organizada. Se quiser, desenhe um exemplo ou explique como usaria em um jogo ou aplicativo!
