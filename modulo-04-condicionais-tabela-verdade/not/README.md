# Aula: Operador Lógico NOT (`!`)

## O que é o operador NOT?

O operador **NOT** (em português, "NÃO") é um dos operadores lógicos mais importantes da programação. Ele serve para inverter o valor de uma expressão booleana. Ou seja, se algo é `verdadeiro` (true), com o NOT vira `falso` (false), e vice-versa.

Pensa assim: é como se você dissesse "NÃO está chovendo". Se está chovendo, a frase é falsa. Se não está, a frase é verdadeira.

## Como usar o NOT em código?

Em muitas linguagens de programação, usamos o símbolo de exclamação `!` para representar o NOT.

Exemplo em JavaScript:

```js
let estaChovendo = true;
console.log(!estaChovendo); // false
```

No exemplo acima, `!estaChovendo` significa "NÃO está chovendo". Como `estaChovendo` é `true`, o resultado é `false`.

## Tabela Verdade do NOT

| Valor original | Resultado com NOT |
|:--------------:|:----------------:|
| true           | false            |
| false          | true             |

Simples, né? O NOT sempre inverte o valor.

## Por que o NOT é importante?

O NOT é muito usado em condições, principalmente quando queremos executar algo **apenas quando uma condição NÃO é verdadeira**.

Exemplo:

```js
if (!temDinheiro) {
    console.log("Não posso comprar o lanche.");
}
```

Aqui, a mensagem só aparece se `temDinheiro` for `false`.

## Exercício rápido

Tente prever o resultado dos seguintes códigos:

```js
let ligado = false;
console.log(!ligado); // ?

let aprovado = true;
console.log(!aprovado); // ?
```

## Explorando mais

Se quiser se aprofundar, veja a pasta [`../and-or`](../and-or/README.md) para entender como o NOT se combina com outros operadores lógicos como AND (`&&`) e OR (`||`).

---

## O que entendi?

> Escreva aqui, com suas próprias palavras, o que você entendeu sobre o operador NOT. Dê exemplos do seu dia a dia ou crie situações engraçadas para fixar o conceito!
