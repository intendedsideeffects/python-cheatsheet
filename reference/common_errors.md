# Common Mistakes

## `=` vs `==`
```python
x = 5      # assignment
x == 5     # comparison
```

## Off-by-one with `range`
```python
range(5)   # 0, 1, 2, 3, 4
```

## Forgetting indentation
```python
if condition:
    print("Indented")
```

## Calling vs referring to a function
```python
len(items)   # call
len          # function object
```

## Mutable list methods often return `None`
```python
cities.sort()        # changes cities in place
sorted(cities)       # returns a new sorted list
```

## Dictionary access
```python
person["age"]        # KeyError if missing
person.get("age")    # returns None if missing
```
