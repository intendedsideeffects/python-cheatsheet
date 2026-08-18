# Functions

## Define and call
```python
def greet(name):
    return f"Hello, {name}!"

message = greet("Janina")
```

## Multiple parameters
```python
def add(a, b):
    return a + b
```

## Default parameter
```python
def greet(name, greeting="Hello"):
    return f"{greeting}, {name}!"
```

## Why `return` matters
`print()` displays a value. `return` sends a value back so it can be stored or reused.
