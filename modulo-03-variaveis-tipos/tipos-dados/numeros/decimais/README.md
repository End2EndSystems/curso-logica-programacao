# Números Decimais

Bem-vindo(a) a mais uma aula! Aqui, vamos explorar um tipo de número muito presente no nosso dia a dia: os **números decimais**.

Eles aparecem quando falamos de dinheiro, medidas, notas de provas e muito mais.

Bora entender como eles funcionam na programação?

---

## O que são números decimais?

Números decimais são aqueles que possuem uma parte inteira e uma parte fracionária, separadas por uma vírgula (ou ponto, na programação). Exemplos:

- 3.14 (pi!)
- 2.5 (dois e meio)
- 0.99 (quase um real!)

Na programação, chamamos esses números de **ponto flutuante** ou **float**.

---

## Como usar números decimais em código?

Vamos ver como declarar e usar números decimais em algumas linguagens populares:

### Python

```python
preco = 19.99
nota = 7.5
print(preco + nota)  # Resultado: 27.49
```

### JavaScript

```javascript
let preco = 19.99;
let nota = 7.5;
console.log(preco + nota); // Resultado: 27.49
```

### Java

```java
double preco = 19.99;
double nota = 7.5;
System.out.println(preco + nota); // Resultado: 27.49
```

---

## Atenção: precisão dos decimais

Os computadores nem sempre conseguem representar números decimais com 100% de precisão. Isso pode causar resultados estranhos, como:

```python
print(0.1 + 0.2)  # Resultado: 0.30000000000000004
```

Por isso, quando for trabalhar com dinheiro ou cálculos muito precisos, existem técnicas e bibliotecas especiais para evitar erros.

---

## Quando usar números decimais?

- Quando precisar representar valores fracionários (meio, um terço, etc).
- Para cálculos de notas, preços, medidas, porcentagens.
- Sempre que o número não for inteiro!

---

## Praticando

Tente criar variáveis com números decimais e fazer operações como soma, subtração, multiplicação e divisão. Veja o que acontece!

---

## O que entendi?

> Escreva aqui, com suas próprias palavras, o que você entendeu sobre números decimais. Dê exemplos do seu dia a dia onde eles aparecem e como você usaria isso em um programa.
