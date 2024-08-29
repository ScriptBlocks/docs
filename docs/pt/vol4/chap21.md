# Capítulo 21: Introdução à Recursão

A recursão ocorre quando uma função chama a si mesma.

## Exemplo

```python
def factorial(n):
    if n == 1:
        return 1
    else:
        return n * factorial(n-1)

print(factorial(5))  # Saída: 120
```