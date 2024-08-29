# Chapter 19: Polymorphism

Polymorphism allows objects of different classes to be treated as objects of a common super class.

## Example

```python
class Cat:
    def speak(self):
        return "Meow"

class Dog:
    def speak(self):
        return "Woof"

animals = [Cat(), Dog()]
for animal in animals:
    print(animal.speak())
```