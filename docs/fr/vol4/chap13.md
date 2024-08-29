# Chapitre 13 : Gestion des erreurs et des exceptions

Des erreurs peuvent survenir lors de l'exécution d'un programme. Python fournit des moyens pour gérer ces exceptions.

## Exemple

```python
try:
    x = int(input("Entrez un nombre : "))
except ValueError:
    print("Ce n'est pas un nombre valide !")
```

Ce code gère le cas où l'entrée n'est pas un entier valide.