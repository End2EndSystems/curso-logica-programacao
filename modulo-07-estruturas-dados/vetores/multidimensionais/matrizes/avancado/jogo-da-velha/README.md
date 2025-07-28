# Jogo da Velha com Matrizes

Bem-vindo ao desafio de criar um **Jogo da Velha** usando matrizes!

Aqui, você vai aprender como usar vetores multidimensionais para construir um dos jogos mais clássicos de todos os tempos.

Preparado para colocar a lógica em prática e desafiar seus amigos?

---

## O que você vai aprender

- Como representar um tabuleiro usando matrizes (vetores 2D)
- Como alternar entre jogadores
- Como verificar se alguém ganhou ou se deu velha (empate)
- Como deixar o jogo mais divertido com lógica de programação

---

## 1. O que é uma Matriz?

Uma matriz é como uma tabela: linhas e colunas.

No Jogo da Velha, o tabuleiro é uma matriz 3x3, ou seja, 3 linhas e 3 colunas.

```js
// Exemplo de matriz 3x3 vazia
let tabuleiro = [
    ["", "", ""],
    ["", "", ""],
    ["", "", ""]
];
```

Cada posição pode ser preenchida com "X", "O" ou ficar vazia.

---

## 2. Montando o Tabuleiro

Vamos criar uma função para mostrar o tabuleiro de forma bonitinha no console:

```js
function mostrarTabuleiro(tabuleiro) {
    for (let linha of tabuleiro) {
        console.log(linha.join(" | "));
    }
}
```

---

## 3. Jogando em Turnos

Você vai precisar alternar entre dois jogadores. Use uma variável para controlar de quem é a vez:

```js
let jogadorAtual = "X";
```

Quando um jogador faz uma jogada, troque para o outro:

```js
jogadorAtual = (jogadorAtual === "X") ? "O" : "X";
```

---

## 4. Fazendo uma Jogada

Para marcar uma posição, peça ao jogador para informar a linha e a coluna. Depois, coloque o símbolo dele na matriz:

```js
tabuleiro[linha][coluna] = jogadorAtual;
```

Não esqueça de verificar se a posição está vazia antes!

---

## 5. Verificando o Vencedor

Depois de cada jogada, verifique se alguém ganhou. Você precisa checar:

- Linhas
- Colunas
- Diagonais

Se todas as posições de uma linha, coluna ou diagonal forem iguais e não estiverem vazias, temos um vencedor!

---

## 6. Empate (Deu Velha!)

Se todas as casas estiverem preenchidas e ninguém ganhou, é empate!

---

## 7. Desafio: Melhorando o Jogo

- Faça o jogo repetir até alguém ganhar ou empatar.
- Mostre mensagens divertidas para os jogadores.
- Que tal desafiar um amigo para jogar com você?

---

## O que entendi?

> Escreva aqui, com suas palavras, o que você aprendeu sobre matrizes e como elas ajudam a criar jogos como o Jogo da Velha. O que foi mais fácil? O que foi mais difícil? O que você faria diferente?
