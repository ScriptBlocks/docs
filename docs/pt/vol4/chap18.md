# Capítulo 18: Herança

A herança permite que uma classe herde atributos e métodos de outra classe.

## Exemplo

```python
class Animal:
    def speak(self):
        print("Som de animal")

class Dog(Animal):
    def speak(self):
        print("Au Au!")

meu_cachorro = Dog()
meu_cachorro.speak()  # Saída: Au Au!
```