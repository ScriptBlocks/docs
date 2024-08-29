# Chapter 20: Encapsulation

Encapsulation restricts access to certain components of an object and is implemented using private variables and methods.

## Example

```python
class Robot:
    def __init__(self, name):
        self.__name = name  # Private variable

    def get_name(self):
        return self.__name

robot = Robot("R2-D2")
print(robot.get_name())  # Outputs: R2-D2
```