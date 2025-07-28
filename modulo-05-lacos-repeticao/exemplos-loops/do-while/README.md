# Aula: Estrutura de Repetição `do...while`

Bem-vindo(a) a mais uma aula! Hoje vamos explorar uma estrutura de repetição muito útil: o `do...while`.

Se você já usou o `while`, vai perceber que eles são parecidos, mas com uma diferença importante.

Bora entender?

---

## O que é o `do...while`?

O `do...while` é um tipo de laço de repetição que **sempre executa o bloco de código pelo menos uma vez**, mesmo que a condição seja falsa logo de cara.

Isso acontece porque a verificação da condição é feita **depois** da execução do bloco.

### Estrutura básica

```javascript
do {
    // bloco de código
} while (condição);
```

- O código dentro do `do { ... }` roda primeiro.
- Depois, a condição é testada.
- Se for verdadeira, repete tudo de novo.
- Se for falsa, o laço termina.

---

## Exemplo prático

Vamos ver um exemplo simples:

```javascript
let numero = 1;

do {
    console.log("Número atual: " + numero);
    numero++;
} while (numero <= 5);
```

**O que acontece aqui?**

- O programa imprime os números de 1 a 5.
- Mesmo se `numero` começasse maior que 5, o bloco rodaria pelo menos uma vez!

---

## Diferença entre `while` e `do...while`

| `while` | `do...while` |
|---------|--------------|
| Testa a condição **antes** de executar o bloco | Executa o bloco **antes** de testar a condição |
| Pode nunca executar o bloco | Sempre executa pelo menos uma vez |

### Exemplo comparativo

```javascript
let x = 10;

while (x < 5) {
    console.log("while: " + x);
}

do {
    console.log("do...while: " + x);
} while (x < 5);
```

- O `while` não imprime nada.
- O `do...while` imprime uma vez: "do...while: 10".

---

## Quando usar o `do...while`?

Use quando você **precisa garantir que o bloco de código execute pelo menos uma vez**.

Exemplos:

- Pedir uma senha até o usuário acertar.
- Mostrar um menu até o usuário escolher sair.

---

## Praticando

Tente criar um programa que:

- Peça ao usuário para digitar um número até que ele digite um número maior que 100.
- Dê dicas se o número for menor ou igual a 100.

```javascript
let numero;

do {
    numero = parseInt(prompt("Digite um número maior que 100:"));
    if (numero <= 100) {
        alert("Tente novamente! O número deve ser maior que 100.");
    }
} while (numero <= 100);

alert("Parabéns! Você digitou: " + numero);
```

---

## O que entendi?

> Escreva aqui, com suas palavras, o que você entendeu sobre o `do...while`, para que serve e quando usaria. Se quiser, coloque exemplos próprios ou dúvidas que surgiram!
