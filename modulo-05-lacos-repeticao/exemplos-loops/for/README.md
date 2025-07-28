# Aula: Estrutura de Repetição `for`

## O que é o `for`?

O `for` é uma estrutura de repetição muito usada na programação.

Ele serve para repetir um bloco de código várias vezes, de forma controlada.

Imagine que você quer dar 10 voltas na quadra: em vez de escrever o mesmo comando 10 vezes, você usa o `for` para automatizar isso!

## Estrutura básica

Veja como é a cara de um `for` em JavaScript:

```javascript
for (let i = 0; i < 10; i++) {
    console.log("Volta número: " + i);
}
```

- **Inicialização:** `let i = 0` → Começa do zero.
- **Condição:** `i < 10` → Repete enquanto for verdade.
- **Incremento:** `i++` → Soma 1 a cada volta.

## Por que usar o `for`?

- Evita repetição de código.
- Facilita mudanças (se quiser 100 voltas, só muda um número!).
- Ajuda a organizar e entender melhor o que está acontecendo.

## Exemplos práticos

### Contando de 1 a 5

```javascript
for (let numero = 1; numero <= 5; numero++) {
    console.log(numero);
}
```

### Somando números de 1 a 10

```javascript
let soma = 0;
for (let i = 1; i <= 10; i++) {
    soma += i;
}
console.log("A soma é: " + soma);
```

### Percorrendo uma lista

```javascript
let frutas = ["maçã", "banana", "uva"];
for (let i = 0; i < frutas.length; i++) {
    console.log(frutas[i]);
}
```

## Dicas para não se perder

- Cuidado com loops infinitos! Se a condição nunca for falsa, o código nunca para.
- O nome da variável (`i`, `j`, etc.) pode ser qualquer um, mas escolha nomes que façam sentido.
- Use o `for` quando souber exatamente quantas vezes quer repetir.

## Explorando mais

Se quiser se aprofundar, veja a pasta [`for/explicacao-detalhada`](./explicacao-detalhada/README.md) para entender cada parte do `for` com mais exemplos e desafios.

## O que entendi?

> Escreva aqui, com suas palavras, o que você entendeu sobre o `for`, para que serve e como pode usar no seu dia a dia de programação!
