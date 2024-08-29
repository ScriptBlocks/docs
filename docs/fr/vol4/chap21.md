# Chapitre 21 : Introduction à la Récursivité

La récursivité se produit lorsqu'une fonction s'appelle elle-même.

## Exemple

```python
def factorial(n):
    if n == 1:
        return 1
    else:
        return n * factorial(n-1)

print(factorial(5))  # Affiche : 120
```