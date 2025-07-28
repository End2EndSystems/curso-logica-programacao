# Aula: Operador Lógico **OR** (`||`)

## O que é o operador OR?

O operador **OR** (ou, em português, "OU") é um dos operadores lógicos mais usados na programação. Ele serve para verificar se **pelo menos uma** das condições é verdadeira. Se **qualquer** condição for verdadeira, o resultado será verdadeiro!

No JavaScript (e em várias outras linguagens), usamos `||` para representar o OR.

---

## Como funciona na prática?

Imagine que você quer sair para brincar, mas só pode se:

- Não estiver chovendo **OU**
- Você tiver um guarda-chuva

Se **uma** dessas condições for verdadeira, você pode sair!

```js
let estaChovendo = false;
let temGuardaChuva = true;

if (estaChovendo == false || temGuardaChuva == true) {
    console.log("Pode sair para brincar!");
} else {
    console.log("Melhor ficar em casa.");
}
```

No exemplo acima, mesmo que esteja chovendo, se você tiver um guarda-chuva, pode sair!

---

## Tabela Verdade do OR

| Condição A | Condição B | A **OR** B |
|:----------:|:----------:|:----------:|
|    false   |   false    |   false    |
|    false   |   true     |   true     |
|    true    |   false    |   true     |
|    true    |   true     |   true     |

**Resumo:** Só dá falso se **todas** as condições forem falsas!

---

## Exemplos do dia a dia

- **Entrar em uma festa:** Você pode entrar se tiver convite **OU** se estiver na lista de convidados.
- **Passar de ano:** Você passa se tirar média suficiente **OU** se for aprovado no conselho.

---

## Exercício rápido

Tente prever o resultado dos códigos abaixo:

```js
console.log(true || false); // ?
console.log(false || false); // ?
console.log(10 > 5 || 2 > 3); // ?
console.log("a" === "b" || 5 === 5); // ?
```

---

## Praticando

Crie um pequeno programa que verifica se uma pessoa pode assistir a um filme:

- Ela pode assistir se for maior de 16 anos **OU** estiver acompanhada de um responsável.

---

## O que entendi?

> Escreva aqui, com suas próprias palavras, o que você entendeu sobre o operador OR (`||`). Dê exemplos do seu dia a dia!
