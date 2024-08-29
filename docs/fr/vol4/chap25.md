# Chapitre 25 : Travailler avec JSON

JSON (JavaScript Object Notation) est un format de données courant utilisé pour les API. Python peut analyser et générer du JSON en utilisant le module `json`.

## Exemple

```python
import json

data = {"name": "Alice", "age": 30, "city": "New York"}
json_data = json.dumps(data)
print(json_data)  # Affiche une chaîne JSON

# Analyser le JSON en un dictionnaire
parsed_data = json.loads(json_data)
print(parsed_data["name"])  # Affiche : Alice
```