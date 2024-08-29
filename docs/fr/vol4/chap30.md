# Chapitre 30 : Introduction aux Tests Unitaires

Les tests unitaires garantissent que les parties individuelles de votre code fonctionnent comme prévu. Le module `unittest` de Python est couramment utilisé à cet effet.

## Exemple

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