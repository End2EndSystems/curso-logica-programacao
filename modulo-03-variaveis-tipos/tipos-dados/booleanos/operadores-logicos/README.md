# Operadores Lógicos em Booleanos

## O que são Operadores Lógicos?

Operadores lógicos são símbolos especiais usados para combinar ou inverter valores booleanos (`true` ou `false`).

Eles são essenciais para criar condições mais complexas em programas, como decidir se um aluno passou de ano ou se pode jogar videogame depois de fazer a lição.

## Principais Operadores Lógicos

### 1. **AND (`&&`)** — E lógico

Só retorna `true` se **todas** as condições forem verdadeiras.

```js
let temIdade = true;
let temAutorizacao = false;

let podeEntrar = temIdade && temAutorizacao; // false
```

### 2. **OR (`||`)** — OU lógico

Retorna `true` se **pelo menos uma** das condições for verdadeira.

```js
let terminouTarefa = false;
let éFimDeSemana = true;

let podeJogar = terminouTarefa || éFimDeSemana; // true
```

### 3. **NOT (`!`)** — NÃO lógico

Inverte o valor booleano.

```js
let estaChovendo = false;

let vouSair = !estaChovendo; // true
```

## Por que usar Operadores Lógicos?

Eles permitem criar regras mais inteligentes no seu código. Por exemplo:

- Só pode sair se terminar a lição **e** arrumar o quarto.
- Pode assistir TV se for sexta-feira **ou** sábado.
- Não pode jogar se **não** fez a tarefa.

## Exemplos Práticos

```js
let fezLicao = true;
let arrumouQuarto = false;

if (fezLicao && arrumouQuarto) {
    console.log("Pode sair para brincar!");
} else {
    console.log("Tem que terminar as tarefas primeiro!");
}
```

```js
let temChuva = true;

if (!temChuva) {
    console.log("Pode ir ao parque!");
} else {
    console.log("Melhor ficar em casa hoje.");
}
```

## Resumindo

- **AND (`&&`)**: todas as condições precisam ser verdadeiras.
- **OR (`||`)**: pelo menos uma condição precisa ser verdadeira.
- **NOT (`!`)**: inverte o valor.

## O que entendi?

> Escreva aqui, com suas próprias palavras, o que você entendeu sobre operadores lógicos. Dê exemplos do seu dia a dia!
