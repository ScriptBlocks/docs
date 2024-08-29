# Chapitre 26 : Expressions Régulières

Les expressions régulières (regex) sont des motifs utilisés pour faire correspondre des chaînes dans un texte. Python fournit le module `re` pour les opérations regex.

## Exemple

```python
import re

pattern = r"\d+"
text = "L'année est 2024"
match = re.search(pattern, text)

if match:
    print(f"Nombre trouvé : {match.group()}")  # Affiche : Nombre trouvé : 2024
```