# Módulo 05: Laços de Repetição

## Por que usar laços de repetição?

Imagina que você precisa pedir para o computador repetir uma tarefa várias vezes, como contar de 1 até 10, mostrar todos os números pares de 0 a 100, ou pedir para o usuário digitar a senha até acertar.

Fazer isso "na mão" seria chato e nada prático, né?

É aí que entram os **laços de repetição** (ou loops)!

Eles são comandos que fazem o computador repetir um bloco de código várias vezes, de forma automática.

## Tipos de laços de repetição

Existem alguns tipos principais de laços de repetição. Vamos conhecer os mais usados:

### 1. `while` (enquanto)

O laço `while` repete um bloco de código **enquanto** uma condição for verdadeira.

```python
contador = 1
while contador <= 5:
    print(contador)
    contador += 1
```

> Esse código vai imprimir os números de 1 a 5.

### 2. `for`

O laço `for` é ótimo quando você já sabe quantas vezes quer repetir algo.

```python
for numero in range(1, 6):
    print(numero)
```

> Aqui, o resultado é igual ao exemplo anterior!

### 3. `do...while` (em algumas linguagens)

Nem toda linguagem tem esse laço, mas ele garante que o bloco de código será executado pelo menos uma vez.

```javascript
let contador = 1;
do {
    console.log(contador);
    contador++;
} while (contador <= 5);
```

## Quando usar cada laço?

- Use `for` quando souber exatamente quantas vezes precisa repetir.
- Use `while` quando não souber quantas vezes vai repetir, mas tem uma condição para parar.
- Use `do...while` quando quiser garantir que o código execute pelo menos uma vez.

## Atenção: loops infinitos

Cuidado para não criar um laço que nunca termina! Isso pode travar seu programa. Sempre pense em como e quando o laço deve parar.

```python
# Exemplo de loop infinito (NÃO FAÇA ISSO!)
while True:
    print("Isso nunca vai parar!")
```

## Explorando mais

Se quiser se aprofundar, confira as pastas abaixo:

- [for/README.md](./for/README.md): Tudo sobre o laço `for` com exemplos práticos.
- [while/README.md](./while/README.md): Entenda o laço `while` e veja dicas para evitar erros comuns.
- [do..while/README.md](./do-while/README.md): Entenda o laço `do..while` e veja a diferença para o `while`.
- [loops-aninhados/README.md](./loops-aninhados/README.md): Como usar laços dentro de laços para resolver problemas mais complexos.

## O que entendi?

> Escreva aqui, com suas palavras, o que você entendeu sobre laços de repetição. Como você acha que pode usar isso para facilitar sua vida na programação?
