# Capítulo 24: Geradores

Os geradores são funções que retornam um conjunto iterável de itens, um de cada vez, utilizando `yield`.

## Exemplo

```python
def count_up_to(max):
    count = 1
    enquanto count <= max:
        yield count
        count += 1

for number in count_up_to(5):
    print(number)
```