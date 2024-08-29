# Chapitre 20 : Encapsulation

L'encapsulation restreint l'accès à certains composants d'un objet et est mise en œuvre à l'aide de variables et de méthodes privées.

## Exemple

```python
class Robot:
    def __init__(self, name):
        self.__name = name  # Variable privée

    def get_name(self):
        return self.__name

robot = Robot("R2-D2")
print(robot.get_name())  # Affiche : R2-D2
```