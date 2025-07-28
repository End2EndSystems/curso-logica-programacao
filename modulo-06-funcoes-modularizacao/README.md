# Módulo 06: Funções e Modularização

Bem-vindo ao sexto módulo do nosso curso de lógica de programação!

Aqui, vamos mergulhar em um dos conceitos mais poderosos da programação: **funções**.

Prepare-se para entender como dividir seu código em partes menores, mais organizadas e reutilizáveis. Bora lá?

---

## O que são Funções?

Imagine que você está jogando um game e precisa repetir a mesma missão várias vezes.

Não seria legal se pudesse apertar um botão e tudo acontecesse automaticamente?

É isso que as funções fazem no código: elas agrupam comandos que podem ser executados sempre que você quiser, sem precisar reescrever tudo de novo.

> **Função** é um bloco de código reutilizável

### Exemplo simples em JavaScript

```javascript
function dizerOla() {
    console.log("Olá, mundo!");
}

dizerOla(); // Chama a função
```

---

## Por que usar Funções?

- **Organização:** Seu código fica mais limpo e fácil de entender.
- **Reutilização:** Você escreve uma vez e usa quantas vezes quiser.
- **Facilidade para corrigir erros:** Se algo der errado, você só precisa arrumar em um lugar.

---

## Parâmetros e Retorno

Funções podem receber informações (parâmetros) e devolver resultados (retorno).

```javascript
function somar(a, b) {
    return a + b;
}

let resultado = somar(5, 3); // resultado = 8
```

- **Parâmetros:** `a` e `b` são valores que você passa para a função.
- **Retorno:** O resultado da soma é devolvido para quem chamou a função.

---

## Modularização: Dividindo para conquistar

Quando seu projeto começa a crescer, fica difícil controlar tudo em um arquivo só.

Aí entra a **modularização**: dividir o código em vários arquivos ou módulos, cada um cuidando de uma parte do sistema.

### Exemplo de estrutura de pastas

```plaintext
meu-projeto/
│
├── main.js
├── funcoes/
│   ├── matematica.js
│   └── texto.js
└── README.md
```

Assim, se precisar de uma função matemática, você sabe exatamente onde procurar!

---

## Praticando: Crie suas próprias funções

1. Crie uma função que receba um nome e imprima uma mensagem de boas-vindas.
2. Crie uma função que calcule a média de três números.
3. Separe suas funções em arquivos diferentes (se estiver usando Node.js ou outro ambiente que permita isso).

---

## O que entendi?

> Escreva aqui, com suas próprias palavras, o que você aprendeu sobre funções e modularização. Como você acha que isso pode te ajudar a programar melhor? Tem alguma dúvida? Anote aqui para perguntar na próxima aula!
