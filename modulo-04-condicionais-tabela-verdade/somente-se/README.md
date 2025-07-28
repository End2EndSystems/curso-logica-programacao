# Operador "Somente Se" (Bicondicional)

Você já percebeu que, em algumas situações, só faz sentido dizer que algo é verdadeiro se outra coisa também for?

É aí que entra o operador **"somente se"**, também chamado de **bicondicional**.

Ele é representado por ↔ ou por <=> em algumas linguagens.

## O que é o operador "somente se"?

O operador "somente se" conecta duas afirmações e só retorna **verdadeiro** quando **ambas** são iguais: ou as duas são verdadeiras, ou as duas são falsas.

Se uma for verdadeira e a outra falsa, o resultado é falso.

### Tabela Verdade do Bicondicional

Veja como funciona na prática:

| A     | B     | A ↔ B |
|-------|-------|-------|
| V     | V     | V     |
| V     | F     | F     |
| F     | V     | F     |
| F     | F     | V     |

- **V** = Verdadeiro
- **F** = Falso

Ou seja, o bicondicional é verdadeiro **somente se** os dois lados forem iguais.

## Exemplo do dia a dia

Imagine que você e seu amigo só vão ao cinema **se ambos quiserem**.

Se os dois quiserem (V, V) ou nenhum quiser (F, F), vocês vão juntos.

Se só um quiser, não rola.

```python
quer_ir_voce = True
quer_ir_amigo = True

if quer_ir_voce == quer_ir_amigo:
    print("Vocês vão ao cinema juntos!")
else:
    print("Vocês não vão ao cinema.")
```

## Por que isso é importante?

O operador bicondicional é muito usado em lógica, matemática e programação para garantir que duas condições estejam em sintonia.

Ele ajuda a criar regras mais precisas e evitar confusões.

---

## O que entendi?

> Escreva aqui, com suas palavras, o que você entendeu sobre o operador "somente se" (bicondicional). Dê exemplos do seu dia a dia ou crie uma situação para praticar!

| [⬅️ Operador Se...Então](../se-e-somente-se/README.md) | Navegação | [Voltar ao Módulo 🏠](../README.md) |
