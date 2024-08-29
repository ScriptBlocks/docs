# Chapter 13: Error and Exception Handling

Errors can occur during the execution of a program. Python provides ways to handle these exceptions.

## Example

```python
try:
    x = int(input("Enter a number: "))
except ValueError:
    print("That's not a valid number!")
```

This code handles the case where the input is not a valid integer.