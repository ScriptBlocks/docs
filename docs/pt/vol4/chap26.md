# Capítulo 26: Expressões Regulares

Expressões regulares (regex) são padrões usados para corresponder strings em texto. O Python fornece o módulo `re` para operações com regex.

## Exemplo

```python
import re

pattern = r"\d+"
text = "O ano é 2024"
match = re.search(pattern, text)

if match:
    print(f"Número encontrado: {match.group()}")  # Exibe: Número encontrado: 2024
```