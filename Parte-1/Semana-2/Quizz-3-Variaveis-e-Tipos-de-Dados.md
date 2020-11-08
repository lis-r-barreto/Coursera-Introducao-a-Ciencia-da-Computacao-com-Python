# Quizz 3 - Variáveis e Tipos de Dados

**Q1.** Qual o tipo de dado armazenado na variável x pelo comando abaixo?

```python
print("Olá")
print()
print("bom dia!")
```

**R1.** a função input sempre devolve um string

**Q2.** Quais os valores finais das variáveis a e b, se o usuário digitar 1 e 2, respectivamente?

```python
a = int(input("Qual o valor de a? "))
b = int(input("Qual o valor de b? "))
a = b
b = a
print(a)
print(b)
```

**R2.** a e b serão 2

**Q3.** Quais os valores finais das variáveis a e b, se o usuário digitar 1 e 2, respectivamente?

```python
a = int(input("Qual o valor de a? "))
b = int(input("Qual o valor de b? "))
aux = a
a = b
b = aux
print(a)
print(b)
```

**R3.** a será 2 e b será 1