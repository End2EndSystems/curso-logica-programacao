# Exemplos Práticos de Pilhas no Dia a Dia

---

## Exemplos de Uso de Pilhas

A estrutura de dados pilha está presente em várias situações cotidianas e aplicações de software. Veja alguns exemplos práticos que podem ser facilmente implementados em Python ou JavaScript:

---

### 1. Desfazer e Refazer em Editores de Texto

**Exemplo em Python:**

```python
desfazer = []
refazer = []

def escrever(acao):
    desfazer.append(acao)
    refazer.clear()

def desfazer_acao():
    if desfazer:
        acao = desfazer.pop()
        refazer.append(acao)
        print(f"Desfez: {acao}")

def refazer_acao():
    if refazer:
        acao = refazer.pop()
        desfazer.append(acao)
        print(f"Refaz: {acao}")

escrever("digitar A")
escrever("digitar B")
desfazer_acao()  # Desfez: digitar B
refazer_acao()   # Refaz: digitar B
```

---

### 2. Navegação em Navegadores Web

**Exemplo em JavaScript:**

```js
let historico = [];

function visitar(pagina) {
  historico.push(pagina);
  console.log("Visitando:", pagina);
}

function voltar() {
  if (historico.length > 0) {
    historico.pop();
    if (historico.length > 0) {
      console.log("Voltando para:", historico[historico.length - 1]);
    } else {
      console.log("Sem páginas para voltar.");
    }
  }
}

visitar("Página 1");
visitar("Página 2");
visitar("Página 3");
voltar(); // Volta para Página 2
voltar(); // Volta para Página 1
```

---

### 3. Verificação de Parênteses Balanceados

**Exemplo em Python:**

```python
def parenteses_balanceados(expr):
    pilha = []
    for char in expr:
        if char == '(':
            pilha.append(char)
        elif char == ')':
            if not pilha:
                return False
            pilha.pop()
    return not pilha

print(parenteses_balanceados("(a + b) * (c + d)"))  # True
print(parenteses_balanceados("(a + b * (c - d)"))   # False
```

---

### 4. Pilha de Pratos

**Exemplo em JavaScript:**

```js
let pratos = [];

function adicionarPrato(prato) {
  pratos.push(prato);
  console.log("Prato adicionado:", prato);
}

function pegarPrato() {
  if (pratos.length > 0) {
    let prato = pratos.pop();
    console.log("Pegou o prato:", prato);
  } else {
    console.log("Sem pratos na pilha.");
  }
}

adicionarPrato("Prato 1");
adicionarPrato("Prato 2");
pegarPrato(); // Pegou o prato: Prato 2
```

---

### 5. Histórico de Comandos em Terminais

**Exemplo em Python:**

```python
historico = []

def executar_comando(comando):
    historico.append(comando)
    print(f"Executando: {comando}")

def comando_anterior():
    if historico:
        print(f"Comando anterior: {historico[-1]}")
    else:
        print("Sem comandos no histórico.")

executar_comando("ls")
executar_comando("cd pasta")
comando_anterior()  # Comando anterior: cd pasta
```

---

## Pratique

- Tente implementar outros exemplos de pilhas, como desfazer/refazer, usando listas em Python ou arrays em JavaScript.
- Experimente adaptar os exemplos acima para outras situações do seu dia a dia.
