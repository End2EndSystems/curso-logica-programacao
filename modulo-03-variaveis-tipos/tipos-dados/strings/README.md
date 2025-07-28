# Strings

Bem-vindo à aula sobre **strings**! Aqui você vai descobrir como trabalhar com textos na programação, entender como funcionam, e aprender truques para deixar seu código ainda mais poderoso.

---

## O que são Strings?

Strings são sequências de caracteres, ou seja, qualquer coisa que você digita entre aspas. Pode ser uma palavra, uma frase, números, símbolos... tudo junto e misturado!

```python
nome = "Maria"
frase = "Hoje é um ótimo dia para aprender programação!"
numero_como_texto = "12345"
```

---

## Como criar uma String

Dependendo da linguagem de programação você pode criar uma string usando aspas simples (`'`) ou duplas (`"`):

```python
mensagem1 = 'Olá, mundo!'
mensagem2 = "Tudo bem?"
```

Ambas funcionam igual, mas cuidado para não misturar!

---

## Caracteres Especiais

Às vezes, você precisa colocar aspas dentro da sua string, ou pular uma linha. Para isso, usamos **caracteres especiais** (chamados de *escape*).

- `\n` pula uma linha
- `\t` adiciona uma tabulação (espaço extra)
- `\\` coloca uma barra dentro da string
- `\"` ou `\'` coloca aspas dentro da string

```python
texto = "Ela disse: \"Oi!\""
poema = "Rosas são vermelhas\nVioletas são azuis"
```

---

## Concatenando Strings

Concatenar é só um nome chique para **juntar strings**. Em Python, usamos o sinal de `+`:

```python
nome = "Lucas"
mensagem = "Olá, " + nome + "!"
print(mensagem)
```

---

## Tamanho da String

Quer saber quantos caracteres tem uma string? Use a função `len()`:

```python
palavra = "programação"
print(len(palavra))  # Vai mostrar 12
```

---

## Acessando Caracteres

Você pode pegar letras específicas de uma string usando colchetes:

```python
texto = "Python"
print(texto[0])  # Mostra 'P'
print(texto[2])  # Mostra 't'
```

Lembre-se: a contagem começa do zero!

---

## Métodos Úteis de Strings

Strings têm vários métodos prontos para facilitar sua vida:

- `.upper()` — deixa tudo MAIÚSCULO
- `.lower()` — deixa tudo minúsculo
- `.replace("a", "e")` — troca letras
- `.strip()` — tira espaços do começo e do fim

```python
mensagem = "  Olá, Mundo!  "
print(mensagem.strip().upper())
```

---

## Exercícios Rápidos

1. Crie uma string com seu nome e mostre quantas letras ela tem.
2. Junte duas frases diferentes em uma só.
3. Troque todas as letras "a" por "@" em uma frase.

---

## O que entendi?

> Escreva aqui, com suas próprias palavras, o que você aprendeu sobre strings. Dê exemplos, explique para você mesmo como se fosse ensinar alguém!

| [⬅️ Tipos de Dados](../README.md) | Navegação | [Voltar a Tipos de Dados 🏠](../README.md) |
