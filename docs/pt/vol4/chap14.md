# Capítulo 14: Trabalhando com Arquivos

Python permite que você trabalhe com arquivos usando a função `open()`.

## Exemplo

```python
with open("example.txt", "w") as file:
    file.write("Olá, Mundo!")
```

Este código escreve "Olá, Mundo!" em um arquivo chamado `example.txt`.