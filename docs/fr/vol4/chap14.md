# Chapitre 14 : Travail avec les fichiers

Python permet de travailler avec des fichiers en utilisant la fonction `open()`.

## Exemple

```python
with open("example.txt", "w") as file:
    file.write("Hello, World!")
```

Ce code écrit "Hello, World!" dans un fichier nommé `example.txt`.