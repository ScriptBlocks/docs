# Capítulo 19: Polimorfismo

O polimorfismo permite que objetos de diferentes classes sejam tratados como objetos de uma superclasse comum.

## Exemplo

```python
class Cat:
    def speak(self):
        return "Miau"

class Dog:
    def speak(self):
        return "Au Au"

animais = [Cat(), Dog()]
for animal in animais:
    print(animal.speak())
```