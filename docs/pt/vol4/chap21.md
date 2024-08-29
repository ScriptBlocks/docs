# Chapter 21: Introduction to Recursion

Recursion occurs when a function calls itself.

## Example

```python
def factorial(n):
    if n == 1:
        return 1
    else:
        return n * factorial(n-1)

print(factorial(5))  # Outputs: 120
```