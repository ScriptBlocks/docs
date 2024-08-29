# Capítulo 17: Classes e Objetos

Python suporta programação orientada a objetos com classes e objetos.

## Exemplo

```python
class Dog:
    def __init__(self, name):
        self.name = name

    def bark(self):
        print(f"{self.name} diz woof!")

meu_cachorro = Dog("Rex")
meu_cachorro.bark()  # Saída: Rex diz woof!
```