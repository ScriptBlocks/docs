# Chapitre 17 : Classes et Objets

Python prend en charge la programmation orientée objet avec les classes et les objets.

## Exemple

```python
class Dog:
    def __init__(self, name):
        self.name = name

    def bark(self):
        print(f"{self.name} dit ouaf !")

my_dog = Dog("Rex")
my_dog.bark()  # Affiche : Rex dit ouaf !
```