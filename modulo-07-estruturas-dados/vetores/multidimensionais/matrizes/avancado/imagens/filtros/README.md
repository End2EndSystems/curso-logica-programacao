# Filtros em Imagens com Matrizes

Bem-vindo(a) a mais uma aula do nosso curso de lógica de programação!

Hoje vamos explorar um tema super interessante: **como aplicar filtros em imagens usando matrizes**.

Você já se perguntou como o Instagram ou o TikTok mudam as cores das fotos?

Ou como é possível deixar uma imagem em preto e branco, ou até borrar uma foto?

Tudo isso é feito com... **matrizes!**

## O que são filtros de imagem?

Filtros de imagem são técnicas que alteram as cores ou detalhes de uma imagem.

Eles funcionam modificando os valores dos pixels, que nada mais são do que números organizados em uma matriz (ou seja, uma tabela de linhas e colunas).

Por exemplo, uma imagem colorida pode ser representada por uma matriz tridimensional: altura x largura x canais de cor (vermelho, verde, azul).

## Como funciona um filtro?

Um filtro percorre cada pixel da imagem e aplica uma regra matemática para mudar seu valor. Por exemplo:

- **Filtro de preto e branco:** transforma cada pixel em tons de cinza.
- **Filtro de brilho:** aumenta ou diminui o valor dos pixels para clarear ou escurecer a imagem.
- **Filtro de desfoque:** faz a média dos pixels vizinhos para suavizar a imagem.

## Exemplo prático: Filtro de Preto e Branco

Vamos imaginar uma imagem bem pequena, de 3x3 pixels, onde cada pixel tem um valor de cor (de 0 a 255):

| 120 | 200 | 90  |
|-----|-----|-----|
| 60  | 180 | 255 |
| 30  | 100 | 220 |

Para transformar em preto e branco, podemos fazer a média dos valores de cada pixel (se fosse colorido, seria a média dos canais R, G e B) e substituir pelo resultado.

```python
# Exemplo em Python
imagem = [
    [120, 200, 90],
    [60, 180, 255],
    [30, 100, 220]
]

for linha in range(len(imagem)):
    for coluna in range(len(imagem[linha])):
        pixel = imagem[linha][coluna]
        # Para preto e branco, mantemos o valor (já é escala de cinza)
        print(pixel, end=' ')
    print()
```

## Explorando outros filtros

Se quiser se aprofundar, crie uma nova pasta chamada `filtros-avancados` e experimente implementar:

- Filtro de brilho
- Filtro de contraste
- Filtro de desfoque (blur)
- Filtro de detecção de bordas

Cada filtro pode ser um arquivo `README.md` separado, explicando o conceito e mostrando exemplos de código.

## Desafio

Pegue uma matriz de imagem (pode ser pequena, como 5x5) e tente criar seu próprio filtro! Pode ser um filtro maluco, invente uma regra matemática e veja o que acontece.

## O que entendi?

> Escreva aqui, com suas palavras, o que você entendeu sobre como funcionam os filtros em imagens usando matrizes. O que mais te chamou atenção? Qual filtro você achou mais legal? Tem alguma dúvida? Compartilhe!
