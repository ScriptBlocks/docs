# Chapitre 18 : Héritage

L'héritage permet à une classe d'hériter des attributs et des méthodes d'une autre classe.

## Exemple

```python
class Animal:
    def speak(self):
        print("Son de l'animal")

class Dog(Animal):
    def speak(self):
        print("Ouaf !")

my_dog = Dog()
my_dog.speak()  # Affiche : Ouaf !
```