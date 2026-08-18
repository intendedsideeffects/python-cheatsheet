# Variables and Types

## Variables
```python
name = "Janina"
age = 43
score = 9.5
is_active = True
```

## Common types
```python
str     # text
int     # whole numbers
float   # decimal numbers
bool    # True / False
list    # ordered, mutable collection
dict    # key-value pairs
tuple   # ordered, immutable collection
set     # unique values
None    # no value
```

## Check and convert types
```python
type(age)
int("42")
float("3.14")
str(42)
bool(1)
```

## Multiple assignment
```python
x, y = 10, 20
```

### Common conversion error

Not every string can be converted to a number:

```python
int("42")       # works
int("hello")    # ValueError
```