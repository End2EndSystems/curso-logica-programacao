# Matrizes Dinâmicas em Outras Linguagens

Agora que você já entendeu como funcionam as matrizes dinâmicas em JavaScript, que tal dar uma olhada em como isso acontece em outras linguagens famosas, como Python e Java? Bora lá!

---

## Python: Simplicidade e Flexibilidade

Em Python, as listas são super flexíveis e podem ser usadas para criar matrizes dinâmicas facilmente. Olha só:

```python
# Criando uma matriz 3x3 em Python
matriz = [
    [1, 2, 3],
    [4, 5, 6],
    [7, 8, 9]
]

# Adicionando uma nova linha
matriz.append([10, 11, 12])

# Adicionando um novo elemento em uma linha existente
matriz[0].append(99)

print(matriz)
```

Python não limita o tamanho das listas, então você pode adicionar ou remover linhas e colunas quando quiser.

Isso deixa tudo muito dinâmico!

---

## Java: Estruturas Mais Rígidas

Java é um pouco diferente.

Aqui, os arrays têm tamanho fixo, mas você pode usar listas (como `ArrayList`) para criar algo mais dinâmico.

Veja:

```java
import java.util.ArrayList;

public class MatrizDinamica {
    public static void main(String[] args) {
        ArrayList<ArrayList<Integer>> matriz = new ArrayList<>();

        // Adicionando linhas
        for (int i = 0; i < 3; i++) {
            matriz.add(new ArrayList<>());
        }

        // Adicionando elementos
        matriz.get(0).add(1);
        matriz.get(0).add(2);
        matriz.get(1).add(3);

        System.out.println(matriz);
    }
}
```

Aqui, usamos `ArrayList` para conseguir adicionar/remover linhas e colunas, deixando a matriz mais flexível.

## C#: Flexibilidade com Listas

Em C#, você pode usar listas genéricas (`List<List<int>>`) para criar matrizes dinâmicas, já que arrays tradicionais têm tamanho fixo. Veja um exemplo:

```csharp
using System;
using System.Collections.Generic;

class Program
{
    static void Main()
    {
        List<List<int>> matriz = new List<List<int>>();

        // Adicionando linhas
        for (int i = 0; i < 3; i++)
        {
            matriz.Add(new List<int>());
        }

        // Adicionando elementos
        matriz[0].Add(1);
        matriz[0].Add(2);
        matriz[1].Add(3);

        // Exibindo a matriz
        foreach (var linha in matriz)
        {
            Console.WriteLine(string.Join(", ", linha));
        }
    }
}
```

Com `List<List<int>>`, você pode adicionar ou remover linhas e colunas facilmente, tornando a matriz dinâmica e flexível, semelhante ao Python e ao Java com `ArrayList`.

---

## Comparando as Linguagens

| Linguagem | Facilidade de uso | Tamanho Dinâmico | Sintaxe |
|-----------|------------------|------------------|---------|
| Python    | Muito fácil      | Sim              | Simples |
| Java      | Médio            | Sim (com listas) | Verboso |
| C#        | Médio            | Sim (com listas) | Verboso |

Cada linguagem tem seu jeitão, mas todas permitem trabalhar com matrizes dinâmicas. O importante é entender o conceito e adaptar para a linguagem que você estiver usando!

---

## O que entendi?

> Escreva aqui, com suas próprias palavras, o que você entendeu sobre matrizes dinâmicas em Python e Java. O que achou mais fácil? O que achou mais difícil? Tem alguma dúvida? Manda ver!
