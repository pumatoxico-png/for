# 🐍 Percorrendo Listas com For

> Exercício de Python sobre acesso e iteração de elementos em listas.

## 🎯 Objetivo
Praticar diferentes maneiras de percorrer uma lista, acessar seus elementos e identificar suas posições.

## 📚 Conceitos utilizados
- Listas (`[]`)
- Indexação (`[0]`)
- Laço de repetição (`for`)
- `range()`
- Iteração sobre listas
- `enumerate()`
- F-strings

## ⚙️ Código

```python
frutas = ['maçã', 'banana', 'uva', 'morango']

print(frutas[0])

for i in range(4):
    print(i)

for fruta in frutas:
    print(fruta)

for indice, fruta in enumerate(frutas):
    print(f'Na posição {indice} está {fruta}')
```

## 📊 Funcionamento

- `frutas[0]`: acessa o primeiro elemento da lista.
- `range(4)`: gera uma sequência de números de 0 a 3.
- `for fruta in frutas`: percorre diretamente os elementos da lista.
- `enumerate(frutas)`: permite percorrer a lista obtendo o índice e o elemento simultaneamente.

## 💻 Exemplo de execução

```text
maçã

0
1
2
3

maçã
banana
uva
morango

Na posição 0 está maçã
Na posição 1 está banana
Na posição 2 está uva
Na posição 3 está morango
```

## 🧠 Aprendizado
Compreensão de diferentes formas de percorrer listas em Python, utilizando laços `for`, sequências numéricas e a função `enumerate()` para acessar índices e elementos.
