# Módulo 04: Condicionais & Tabela Verdade

## Introdução

Você já percebeu como tomamos decisões o tempo todo? "Se chover, levo guarda-chuva. Se não, vou de bicicleta."

No mundo da programação, usamos **condicionais** para ensinar o computador a tomar decisões por conta própria.

E para entender como essas decisões funcionam, precisamos conhecer a **tabela verdade**.

## O que são Condicionais?

Condicionais são comandos que dizem ao computador: "Faça isso SE tal coisa acontecer". O mais comum é o famoso `if` (se), mas também temos `else` (senão) e `elif` (senão se).

Exemplo em Python:

```python
idade = 16
if idade >= 18:
    print("Você pode dirigir!")
else:
    print("Ainda não pode dirigir.")
```

## Por que usar Condicionais?

Imagine um jogo:

- se o jogador encostar no inimigo, perde uma vida.
- se pegar uma moeda, ganha pontos.

Sem condicionais, seria impossível criar regras e desafios!

## Tabela Verdade: O que é isso?

A tabela verdade é uma ferramenta que mostra todas as possibilidades de verdadeiro (True) ou falso (False) em uma expressão lógica. Ela é essencial para entender como o computador avalia condições.

### Operadores Lógicos

- **AND** (e): Só é verdadeiro se TUDO for verdadeiro.
- **OR** (ou): É verdadeiro se PELO MENOS UM for verdadeiro.
- **NOT** (não): Inverte o valor (True vira False e vice-versa).

### Tabela Verdade do AND

| A     | B     | A AND B |
|-------|-------|---------|
| True  | True  | True    |
| True  | False | False   |
| False | True  | False   |
| False | False | False   |

### Tabela Verdade do OR

| A     | B     | A OR B  |
|-------|-------|---------|
| True  | True  | True    |
| True  | False | True    |
| False | True  | True    |
| False | False | False   |

### Tabela Verdade do NOT

| A     | NOT A |
|-------|-------|
| True  | False |
| False | True  |

## Praticando

Tente prever o que será impresso:

```python
chovendo = False
tem_guarda_chuva = True

if chovendo and tem_guarda_chuva:
    print("Pode sair tranquilo!")
else:
    print("Melhor ficar em casa.")
```

O que acontece se mudar `chovendo` para `True`?

## Explorando Mais

Se quiser se aprofundar, vamos explorar cada tipo de tabela verdade em detalhes:

- **[Tabela Verdade do AND (E)](./and/)**: Veja como diferentes combinações de verdadeiro e falso afetam o resultado quando usamos o operador `and`.
- **[Tabela Verdade do OR (OU)](./or/)**: Entenda como o operador `or` funciona e quando o resultado será verdadeiro ou falso.
- **[Tabela Verdade do NOT (NÃO)](./not/)**: Descubra como o operador `not` inverte o valor lógico de uma expressão.
- **[Tabela Verdade do SE (IMPLICAÇÃO)](./se-e-somente-se/)**: Entenda como funciona o operador "se... então" (implicação lógica), que só é falso quando a primeira condição é verdadeira e a segunda é falsa.
- **[Tabela Verdade do SOMENTE SE (BICONDICIONAL)](./somente-se/)**: Veja como o operador "somente se" (bicondicional) é verdadeiro apenas quando ambos os valores são iguais.

Nos próximos tópicos, você encontrará exemplos práticos e exercícios para cada operador. Assim, ficará mais fácil entender como usar essas tabelas para tomar decisões em seus programas!

## O que entendi?

> Escreva aqui, com suas palavras, o que você entendeu sobre condicionais e tabela verdade. Dê exemplos do seu dia a dia ou crie situações engraçadas para fixar o conteúdo!

|   | Navegação |   |
|:-:|:----------|:-:|
| [⬅️ Módulo Anterior](../modulo-03-variaveis-tipos/README.md) |  | [Próximo Módulo ➡️](../modulo-05-lacos-repeticao/README.md) |
