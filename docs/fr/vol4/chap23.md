# Chapitre 23 : Décorateurs

Les décorateurs sont des fonctions qui modifient le comportement d'une autre fonction.

## Exemple

```python
def my_decorator(func):
    def wrapper():
        print("Quelque chose se passe avant l'appel de la fonction.")
        func()
        print("Quelque chose se passe après l'appel de la fonction.")
    return wrapper

@my_decorator
def say_hello():
    print("Bonjour!")

say_hello()
```