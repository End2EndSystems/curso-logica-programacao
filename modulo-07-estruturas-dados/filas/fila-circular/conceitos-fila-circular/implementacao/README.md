# Implementação de Fila Circular

Agora que você já entendeu o conceito de fila circular, chegou a hora de colocar a mão na massa!

Vamos ver como implementar uma fila circular na prática e entender por que ela é tão útil em situações do dia a dia da programação.

---

## O que é uma Fila Circular?

Uma fila circular é uma estrutura de dados que funciona como uma fila comum (FIFO: First In, First Out), mas com um detalhe especial: quando o final da fila é alcançado, ela "dá a volta" e começa a preencher os espaços vazios no início do array.

Isso evita desperdício de espaço e torna a estrutura mais eficiente.

Imagine uma roda gigante: quando um assento fica vazio, ele pode ser ocupado novamente quando a roda gira.

Assim funciona a fila circular!

---

## Por que usar uma Fila Circular?

- **Eficiência:** Aproveita melhor o espaço do array, evitando que posições fiquem inutilizadas.
- **Desempenho:** Operações de inserção e remoção são rápidas, pois não é necessário mover elementos.
- **Aplicações reais:** Muito usada em sistemas de impressão, buffers de áudio/vídeo, gerenciamento de tarefas, entre outros.

---

## Como funciona a implementação?

A implementação de uma fila circular geralmente envolve:

- Um array fixo para armazenar os elementos.
- Dois ponteiros (ou índices): `inicio` e `fim`.
- Uma lógica para "dar a volta" quando o final do array é alcançado (usando o operador de módulo `%`).

Exemplo de lógica para avançar o ponteiro:

```python
fim = (fim + 1) % tamanho_maximo
```

---

## Explorando o Código

Se quiser se aprofundar mais, confira a pasta `implementacao` para ver exemplos práticos de código! Lá você vai encontrar implementações comentadas e exemplos de uso para testar e entender cada detalhe.

---

## O que entendi?

> Escreva aqui, com suas próprias palavras, o que você entendeu sobre filas circulares, para que servem e como funcionam. Se ficou alguma dúvida, anote também para perguntar depois!
