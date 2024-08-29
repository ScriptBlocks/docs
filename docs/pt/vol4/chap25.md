# Chapter 25: Working with JSON

JSON (JavaScript Object Notation) is a common data format used for APIs. Python can parse and generate JSON using the `json` module.

## Example

```python
import json

data = {"name": "Alice", "age": 30, "city": "New York"}
json_data = json.dumps(data)
print(json_data)  # Outputs a JSON string

# Parse JSON back to a dictionary
parsed_data = json.loads(json_data)
print(parsed_data["name"])  # Outputs: Alice
```