# Chapter 14: Working with Files

Python allows you to work with files using the `open()` function.

## Example

```python
with open("example.txt", "w") as file:
    file.write("Hello, World!")
```

This code writes "Hello, World!" to a file named `example.txt`.