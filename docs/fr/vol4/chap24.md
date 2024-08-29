# Chapitre 24 : Générateurs

Les générateurs sont des fonctions qui renvoient un ensemble d'éléments itérables, un à la fois, en utilisant `yield`.

## Exemple

```python
def count_up_to(max):
    count = 1
    while count <= max:
        yield count
        count += 1

for number in count_up_to(5):
    print(number)
```