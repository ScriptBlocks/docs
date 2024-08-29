# Chapter 26: Regular Expressions

Regular expressions (regex) are patterns used to match strings in text. Python provides the `re` module for regex operations.

## Example

```python
import re

pattern = r"\d+"
text = "The year is 2024"
match = re.search(pattern, text)

if match:
    print(f"Found a number: {match.group()}")  # Outputs: Found a number: 2024
```