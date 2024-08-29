# Chapter 30: Introduction to Unit Testing

Unit testing ensures that individual parts of your code work as expected. Python's `unittest` module is commonly used for this.

## Example

```python
import unittest

def add(x, y):
    return x + y

class TestAdd(unittest.TestCase):
    def test_add(self):
        self.assertEqual(add(2, 3), 5)

if __name__ == '__main__':
    unittest.main()
```