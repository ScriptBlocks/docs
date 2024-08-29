# Capítulo 20: Encapsulamento

O encapsulamento restringe o acesso a certos componentes de um objeto e é implementado usando variáveis e métodos privados.

## Exemplo

```python
class Robot:
    def __init__(self, name):
        self.__name = name  # Variável privada

    def get_name(self):
        return self.__name

robot = Robot("R2-D2")
print(robot.get_name())  # Saída: R2-D2
```