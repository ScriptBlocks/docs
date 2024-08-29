# Capítulo 30: Introdução aos Testes Unitários

Os testes unitários garantem que partes individuais do seu código funcionem como esperado. O módulo `unittest` do Python é comumente usado para isso.

## Exemplo

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