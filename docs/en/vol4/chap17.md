# Chapter 17: Classes and Objects

Python supports object-oriented programming with classes and objects.

## Example

```python
class Dog:
    def __init__(self, name):
        self.name = name

    def bark(self):
        print(f"{self.name} says woof!")

my_dog = Dog("Rex")
my_dog.bark()  # Outputs: Rex says woof!
```