# Aula: Estruturas de Repetição - While

Bem-vindo(a) a mais uma etapa da sua jornada na programação!

Hoje vamos explorar um dos conceitos mais importantes e poderosos: **laços de repetição**, mais especificamente o `while`.

Prepare-se para entender como fazer o computador repetir tarefas automaticamente, sem precisar copiar e colar código!

---

## O que é um laço de repetição?

Imagine que você precisa pedir para alguém contar de 1 até 10.

Você não vai pedir para a pessoa falar cada número individualmente, certo?

Você só diz: "Conte de 1 até 10".

O laço de repetição faz exatamente isso com o computador: ele repete um bloco de código várias vezes, até que uma condição seja satisfeita.

---

## Conhecendo o `while`

O `while` é um tipo de laço de repetição que executa um bloco de código **enquanto** uma condição for verdadeira.

```python
contador = 1
while contador <= 5:
    print(contador)
    contador += 1
```

No exemplo acima, o computador vai imprimir os números de 1 a 5. Ele só para quando a condição (`contador <= 5`) não for mais verdadeira.

---

## Como funciona o `while`?

1. **Verifica a condição**: Antes de executar o bloco, o `while` checa se a condição é verdadeira.
2. **Executa o bloco**: Se for verdadeira, executa o bloco de código.
3. **Repete**: Volta para o passo 1.

Se a condição nunca mudar para falsa, o laço nunca termina! Isso é chamado de **loop infinito**. Tome cuidado!

---

## Exemplo prático: adivinhando um número

Vamos criar um jogo simples onde o usuário precisa adivinhar um número:

```python
numero_secreto = 7
palpite = int(input("Adivinhe o número: "))

while palpite != numero_secreto:
    print("Errou! Tente novamente.")
    palpite = int(input("Adivinhe o número: "))

print("Parabéns! Você acertou!")
```

---

## Dicas para não cair em armadilhas

- Sempre garanta que a condição do `while` pode se tornar falsa em algum momento.
- Use variáveis de controle (como o `contador`).
- Se precisar sair do laço antes da condição, use o comando `break`.

---

## O que entendi?

> Escreva aqui, com suas palavras, o que você entendeu sobre o laço `while`, para fixar o conteúdo e tirar dúvidas depois.
