# Aula: Operador Lógico AND (`&&`)

Bem-vindo(a) a mais uma etapa da nossa jornada pela lógica de programação! Hoje vamos mergulhar no operador lógico **AND** (em português, **E**), um dos blocos fundamentais para criar condições mais complexas no seu código.

---

## O que é o operador AND?

O operador **AND** (`&&`) serve para combinar duas ou mais condições. Ele só retorna **verdadeiro** se **todas** as condições forem verdadeiras ao mesmo tempo.

Pense assim: para sair com os amigos, você precisa **ter permissão dos pais** **E** **ter feito a lição de casa**. Se faltar qualquer uma dessas, nada de rolê!

---

## Tabela Verdade do AND

| Condição A | Condição B | Resultado (A && B) |
|:----------:|:----------:|:------------------:|
|    true    |    true    |       true         |
|    true    |   false    |       false        |
|   false    |    true    |       false        |
|   false    |   false    |       false        |

Ou seja: **só dá true se tudo for true!**

---

## Exemplos práticos

### Exemplo 1: Entrada em uma festa

```js
let temConvite = true;
let idadeMaiorDe18 = false;

if (temConvite && idadeMaiorDe18) {
    console.log("Pode entrar na festa!");
} else {
    console.log("Entrada não permitida.");
}
```

Neste caso, mesmo tendo convite, se não for maior de 18, não entra!

---

### Exemplo 2: Login em um site

```js
let usuarioCorreto = true;
let senhaCorreta = true;

if (usuarioCorreto && senhaCorreta) {
    console.log("Login realizado com sucesso!");
} else {
    console.log("Usuário ou senha incorretos.");
}
```

Aqui, só faz login se **os dois** estiverem certos.

---

## Praticando

Tente criar situações do seu dia a dia onde você só pode fazer algo se **duas ou mais condições** forem verdadeiras. Escreva essas situações como se fossem códigos!

---

## Explorando mais

Se quiser se aprofundar, confira a pasta [`../or/`](../or/README.md) para aprender sobre o operador **OR** (`||`), que funciona de um jeito diferente!

---

## O que entendi?

> Escreva aqui, com suas palavras, o que você entendeu sobre o operador AND (`&&`). Dê exemplos do seu cotidiano ou crie situações imaginárias para fixar o conceito!

| [⬅️ Voltar ao Módulo](../README.md) | Navegação | [Próximo Operador ➡️](../or/README.md) |
