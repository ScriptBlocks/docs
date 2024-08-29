# Capítulo 25: Trabalhando com JSON

JSON (JavaScript Object Notation) é um formato de dados comum usado para APIs. O Python pode analisar e gerar JSON usando o módulo `json`.

## Exemplo

```python
import json

data = {"name": "Alice", "age": 30, "city": "New York"}
json_data = json.dumps(data)
print(json_data)  # Exibe uma string JSON

# Analisar o JSON de volta para um dicionário
parsed_data = json.loads(json_data)
print(parsed_data["name"])  # Exibe: Alice
```