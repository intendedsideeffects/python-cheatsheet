# Sets and Tuples

## Tuples
Ordered and immutable.
```python
coordinates = (52.52, 13.405)
coordinates[0]
```

## Sets
Unordered collection of unique values.
```python
cities = {"Berlin", "Paris", "Berlin"}
# duplicate Berlin is removed

cities.add("London")
cities.remove("Paris")
```

Useful for removing duplicates:
```python
unique_values = set([1, 1, 2, 3])
```
