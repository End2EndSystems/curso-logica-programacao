# Booleanos

## O que são booleanos?

Booleanos são um tipo de dado muito importante na programação.

Eles só têm **dois valores possíveis**: `true` (verdadeiro) ou `false` (falso).

Sim, só isso! Eles servem para responder perguntas do tipo **sim ou não**.

Por exemplo:

- Você terminou a lição? `true` ou `false`
- A luz está acesa? `true` ou `false`
- O usuário está logado? `true` ou `false`

## Por que booleanos são importantes?

Com booleanos, conseguimos **tomar decisões** no nosso código.

Eles são a base para comandos como `if`, `else`, e loops.

Sem eles, seria impossível fazer programas que reagem a situações diferentes.

## Como criar booleanos em JavaScript

```js
let estaChovendo = true;
let terminouTarefa = false;
```

Você também pode obter valores booleanos a partir de comparações:

```js
let idade = 16;
let podeDirigir = idade >= 18; // false
```

## Operadores lógicos

Os operadores lógicos ajudam a combinar ou inverter valores booleanos:

- **E (`&&`)**: Só é `true` se os dois lados forem `true`.
- **OU (`||`)**: É `true` se pelo menos um lado for `true`.
- **NÃO (`!`)**: Inverte o valor (`true` vira `false` e vice-versa).

Exemplo:

```js
let temCarteira = false;
let temIdade = true;

let podeDirigir = temCarteira && temIdade; // false
let podeEntrar = temCarteira || temIdade; // true
let naoTemCarteira = !temCarteira; // true
```

## Exercício rápido

1. Crie uma variável chamada `estaComFome` e coloque o valor `true`.
2. Crie uma variável chamada `temComida` e coloque o valor `false`.
3. Crie uma variável chamada `vaiComer` que só será `true` se `estaComFome` **e** `temComida` forem `true`.

```js
let estaComFome = true;
let temComida = false;
let vaiComer = estaComFome && temComida; // false
```

## Explorando mais

Se quiser se aprofundar, veja a pasta [`operadores-logicos`](../operadores-logicos/README.md) para entender melhor como funcionam as combinações de booleanos.

---

## O que entendi?

> Escreva aqui, com suas palavras, o que você entendeu sobre booleanos, para que servem e como usá-los no seu código!
