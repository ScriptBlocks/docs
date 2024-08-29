# Chapitre 19 : Polymorphisme

Le polymorphisme permet de traiter des objets de différentes classes comme des objets d'une classe de base commune.

## Exemple

```python
class Cat:
    def speak(self):
        return "Miaou"

class Dog:
    def speak(self):
        return "Ouaf"

animals = [Cat(), Dog()]
for animal in animals:
    print(animal.speak())
```