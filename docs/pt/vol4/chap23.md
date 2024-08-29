# Capítulo 23: Decoradores

Os decoradores são funções que modificam o comportamento de outra função.

## Exemplo

```python
def my_decorator(func):
    def wrapper():
        print("Algo está acontecendo antes da função ser chamada.")
        func()
        print("Algo está acontecendo depois da função ser chamada.")
    return wrapper

@my_decorator
def say_hello():
    print("Olá!")

say_hello()
```