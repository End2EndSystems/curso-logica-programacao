# Busca em Matrizes: Como Encontrar o que Você Procura?

Bem-vindo(a) a mais uma aula!

Hoje vamos aprender como buscar informações dentro de matrizes (ou tabelas).

Sabe quando você quer encontrar um nome em uma lista de presença ou um valor específico em uma tabela de jogos?

É exatamente isso que vamos explorar!

---

## O que é uma Busca em Matrizes?

Buscar em uma matriz significa procurar por um valor específico dentro de uma tabela de dados.

Imagine uma planilha do Excel: cada célula pode conter um dado, e você precisa encontrar onde está o que procura.

Existem dois tipos principais de busca:

- **Busca Linear:** Procura célula por célula, linha por linha.
- **Busca Otimizada:** Usa técnicas para acelerar a busca (vamos focar na linear por enquanto).

---

## Exemplo Prático: Procurando um Número

Vamos supor que temos a seguinte matriz:

```python
matriz = [
    [5, 8, 12],
    [7, 3, 9],
    [4, 6, 11]
]
```

E queremos saber se o número `9` está presente.

### Código para Busca Linear

```python
def buscar_numero(matriz, numero):
    for i in range(len(matriz)):
        for j in range(len(matriz[i])):
            if matriz[i][j] == numero:
                return (i, j)  # Retorna a posição (linha, coluna)
    return None

posicao = buscar_numero(matriz, 9)

if posicao:
    print(f"Número encontrado na linha {posicao[0]}, coluna {posicao[1]}")
else:
    print("Número não encontrado.")
```

---

## Dicas para Não se Perder

- Sempre use dois loops: um para as linhas, outro para as colunas.
- Cuidado com os índices! Eles começam do zero.
- Se precisar buscar mais de um valor, pode adaptar o código para guardar todas as posições encontradas.

---

## Desafio: Busque um Nome

Imagine uma matriz de nomes de alunos.

Tente criar um código que busque o nome de um colega e diga em que posição ele está!

---

## Indo Mais Fundo

Se quiser se aprofundar em buscas mais rápidas (como busca binária em matrizes ordenadas), confira a pasta [`busca-avancada`](./busca-avancada/README.md) para exemplos e desafios extras!

---

## O que entendi?

> Escreva aqui, com suas palavras, o que você entendeu sobre busca em matrizes. Dê exemplos do seu dia a dia onde isso pode ser útil!
