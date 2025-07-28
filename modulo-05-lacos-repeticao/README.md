# Módulo 05: Laços de Repetição

Bem-vindo ao quinto módulo do nosso curso de lógica de programação! Aqui, vamos explorar um dos conceitos mais poderosos e usados em programação: **laços de repetição**. Prepare-se para automatizar tarefas repetitivas e deixar seus códigos muito mais eficientes!

---

## O que são Laços de Repetição?

Laços de repetição (ou loops) são estruturas que permitem executar um bloco de código várias vezes, de acordo com uma condição. Eles são essenciais para resolver problemas que envolvem repetição, como percorrer listas, contar números ou pedir informações ao usuário até que ele acerte uma resposta.

> **Laço** (ou **loop**) é uma estrutura que repete comandos várias vezes.  
> Cada repetição é chamada de **iteração**.

---

## Tipos de Laços

### 1. **Laço `while`**

O laço `while` executa um bloco de código **enquanto** uma condição for verdadeira.

```python
contador = 1
while contador <= 5:
    print(contador)
    contador += 1
```

> O código acima imprime os números de 1 a 5.

### 2. **Laço `for`**

O laço `for` é usado quando sabemos exatamente quantas vezes queremos repetir algo.

```python
for i in range(1, 6):
    print(i)
```

> Também imprime os números de 1 a 5, mas de uma forma mais compacta.

### 3. **Laço `do...while` (simulado em Python)**

Python não tem um laço `do...while` nativo, mas podemos simular:

```python
while True:
    resposta = input("Digite 'sair' para encerrar: ")
    if resposta == 'sair':
        break
```

> O bloco será executado pelo menos uma vez, e só para quando a condição for satisfeita.

---

## Por que usar laços?

Imagine pedir para um computador imprimir os números de 1 a 1000. Você não vai escrever mil linhas de código, certo? Com laços, isso é feito em segundos! Eles também ajudam a processar listas, validar dados e criar jogos interativos.

---

## Praticando

1. **Contando até 10:**  
   Escreva um programa que conte de 1 a 10 usando um laço `while`.

2. **Tabuada:**  
   Peça ao usuário um número e mostre a tabuada desse número usando um laço `for`.

3. **Adivinhação:**  
   Crie um jogo simples onde o usuário deve adivinhar um número secreto. Use um laço para continuar perguntando até acertar.

---

## Explorando Mais

Se quiser se aprofundar, confira a pasta [`exemplos-loops`](./exemplos-loops/README.md) com exemplos práticos e desafios extras!

---

## O que entendi?

> Escreva aqui, com suas próprias palavras, o que você entendeu sobre laços de repetição. Como eles podem te ajudar a resolver problemas? Qual tipo de laço você achou mais interessante?  
>
> _Exemplo: "Entendi que laços servem para repetir comandos sem precisar copiar e colar várias vezes. Achei o `for` legal porque é simples de usar para listas."_

|   | Navegação |   |
|:-:|:----------|:-:|
| [⬅️ Módulo Anterior](../modulo-04-condicionais-tabela-verdade/README.md) |  | [Próximo Módulo ➡️](../modulo-06-funcoes-modularizacao/README.md) |
