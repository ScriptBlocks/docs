# Chapter 18: Inheritance

Inheritance allows a class to inherit attributes and methods from another class.

## Example

```python
class Animal:
    def speak(self):
        print("Animal sound")

class Dog(Animal):
    def speak(self):
        print("Woof!")

my_dog = Dog()
my_dog.speak()  # Outputs: Woof!
```