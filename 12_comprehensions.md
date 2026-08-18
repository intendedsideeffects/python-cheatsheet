# Comprehensions

A compact way to create collections. Prefer a normal loop when the expression becomes difficult to read.

## List comprehension
```python
squares = [x ** 2 for x in range(5)]
```

## With condition
```python
even_numbers = [x for x in range(10) if x % 2 == 0]
```

Equivalent loop:
```python
even_numbers = []
for x in range(10):
    if x % 2 == 0:
        even_numbers.append(x)
```
