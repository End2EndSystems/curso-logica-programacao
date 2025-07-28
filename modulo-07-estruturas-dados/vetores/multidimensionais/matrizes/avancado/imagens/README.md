# Matrizes Avançado: Manipulando Imagens com Estruturas Multidimensionais

Seja bem-vindo(a) a mais um nível da sua jornada em programação!

Aqui, vamos explorar como as **matrizes multidimensionais** são ferramentas poderosas para manipular imagens — sim, aquelas fotos e desenhos que você vê na tela!

---

## Por Que Matrizes São Tão Importantes em Imagens?

Você já parou para pensar como uma imagem é formada no computador?

Cada imagem é, na verdade, uma grande tabela de números!

Cada "caixinha" dessa tabela representa um pixel, e cada pixel tem informações sobre cor e brilho.

- **Imagens em preto e branco:** Cada pixel é um número (0 = preto, 255 = branco).
- **Imagens coloridas:** Cada pixel é um conjunto de três números (R, G, B — vermelho, verde, azul).

Ou seja, uma imagem nada mais é do que uma **matriz 2D** (ou até 3D, se pensarmos nas cores)!

---

## Como Representar Imagens com Matrizes?

Vamos ver exemplos práticos em **JavaScript** e **Python**:

### JavaScript

```js
// Imagem 3x3 em preto e branco (valores de 0 a 255)
let imagemPB = [
    [0, 128, 255],
    [255, 128, 0],
    [0, 255, 128]
];

// Imagem 2x2 colorida (cada pixel tem [R, G, B])
let imagemColorida = [
    [ [255,0,0], [0,255,0] ],
    [ [0,0,255], [255,255,0] ]
];

// Acessando o pixel da linha 1, coluna 2 (cor verde)
console.log(imagemColorida[0][1]); // [0, 255, 0]
```

### Python

```python
# Imagem 3x3 em preto e branco
imagem_pb = [
        [0, 128, 255],
        [255, 128, 0],
        [0, 255, 128]
]

# Imagem 2x2 colorida (cada pixel é [R, G, B])
imagem_colorida = [
        [ [255,0,0], [0,255,0] ],
        [ [0,0,255], [255,255,0] ]
]

# Acessando o pixel da linha 1, coluna 2 (cor verde)
print(imagem_colorida[0][1])  # [0, 255, 0]
```

---

## O Que Podemos Fazer com Matrizes de Imagem?

Manipular imagens é como brincar de editor de fotos, só que programando! Veja algumas ideias:

- **Inverter as cores:** Trocar cada valor por `255 - valor`.
- **Deixar a imagem em preto e branco:** Calcular a média dos valores RGB de cada pixel.
- **Desenhar formas:** Alterar valores de pixels específicos para criar desenhos.
- **Aplicar filtros:** Como borrar, destacar bordas, etc.

Se quiser se aprofundar nesses efeitos, confira a pasta [`filtros`](./filtros/README.md) para exemplos práticos e desafios!

---

## Desafio: Renderizando uma Imagem no Console

Que tal um desafio prático? Pegue uma matriz que representa uma imagem em preto e branco e escreva um código JavaScript para "desenhar" essa imagem no console do navegador!

Por exemplo, use a matriz abaixo, onde `0` representa um espaço em branco e `1` representa um pixel preenchido (`#`):

```js
let imagem = [
    [0, 1, 0, 1, 0],
    [1, 0, 1, 0, 1],
    [0, 1, 0, 1, 0],
    [1, 0, 1, 0, 1],
    [0, 1, 0, 1, 0]
];

// Seu desafio: percorra a matriz e use console.log para mostrar a imagem no console, usando "#" para 1 e " " para 0.
```

Tente criar diferentes padrões e experimente alterar os valores da matriz para ver como a "imagem" muda no console!

---

## Dicas Para Não Se Perder

- Desenhe a matriz da imagem no papel para entender como os pixels estão organizados.
- Use variáveis com nomes claros, como `linha`, `coluna`, `pixel`.
- Teste com imagens pequenas antes de tentar manipular fotos grandes.

---

## O que entendi?

> Escreva aqui, com suas próprias palavras, o que você entendeu sobre como as matrizes podem ser usadas para manipular imagens, criar jogos e aplicar efeitos. Se ficou alguma dúvida, anote também!
