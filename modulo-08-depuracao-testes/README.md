# Módulo 08: Depuração e Testes

---

## Por que depurar e testar?

Você já passou horas tentando entender por que seu código não funciona? Bem-vindo ao mundo real da programação! Depuração e testes são como superpoderes que ajudam a encontrar e corrigir erros antes que eles virem um problemão.

---

## O que é depuração?

Depurar é o processo de identificar e corrigir erros (bugs) no seu código. É como ser um detetive: você precisa investigar, seguir pistas e descobrir onde as coisas estão dando errado.

### Ferramentas de depuração

- **Prints**: O clássico `print()` para ver o que está acontecendo.
- **Depurador (Debugger)**: Ferramentas que permitem pausar o código, examinar variáveis e avançar passo a passo.
- **IDE**: Muitas IDEs (como VSCode ou PyCharm) têm depuradores embutidos.

---

## O que são testes?

Testar é garantir que seu código faz o que deveria fazer. Existem vários tipos de testes, mas vamos focar nos mais usados por quem está começando:

- **Testes manuais**: Você mesmo executa o programa e verifica se tudo está certo.
- **Testes automatizados**: Você escreve códigos que testam outros códigos! Assim, sempre que mudar algo, pode rodar os testes e ver se quebrou alguma coisa.

> **Depuração** é o processo de encontrar e corrigir erros (bugs) no código.  
> **Teste** é uma forma de verificar se o código está funcionando como esperado.

---

## Como depurar na prática?

1. **Leia a mensagem de erro**: Ela geralmente diz onde está o problema.
2. **Use prints estratégicos**: Mostre valores de variáveis em pontos importantes.
3. **Teste partes menores**: Separe funções e teste uma de cada vez.
4. **Use o depurador da sua IDE**: Coloque breakpoints e veja o código rodando passo a passo.

---

## Como criar testes simples?

Vamos criar um teste básico em Python usando `assert`:

```python
def soma(a, b):
    return a + b

# Teste
assert soma(2, 3) == 5
assert soma(-1, 1) == 0
```

Se algum teste falhar, o Python vai avisar!

---

## Explorando mais: Testes Automatizados

Se quiser se aprofundar, crie uma pasta chamada `testes-automatizados` e veja como usar bibliotecas como `unittest` ou `pytest` para criar testes mais avançados.

---

## Dicas para não se perder

- Teste seu código sempre que fizer uma mudança.
- Não tenha medo de errar! Errar faz parte do processo.
- Use as ferramentas a seu favor: prints, depurador, testes automatizados.

---

## O que entendi?

> Escreva aqui, com suas próprias palavras, o que você entendeu sobre depuração e testes. O que achou mais interessante? Teve alguma dúvida? Anote tudo aqui!

|   | Navegação |   |
|:-:|:----------|:-:|
| [⬅️ Módulo Anterior](../modulo-07-estruturas-dados/README.md) |  | [Próximo Módulo ➡️](../modulo-09-problemas-logicos/README.md) |
