# Lists

Lists store multiple values in an ordered, mutable collection.

## Create
```python
cities = ["Berlin", "Paris", "London"]
```

## Access and slice
```python
cities[0]
cities[-1]
cities[0:2]
```

## Change
```python
cities[1] = "Madrid"
```

## Add and remove
```python
cities.append("Rome")
cities.insert(1, "Hamburg")
cities.remove("Berlin")
last_city = cities.pop()
```

## Useful operations
```python
len(cities)
"Berlin" in cities
cities.count("Berlin")
cities.index("London")
cities.sort()
cities.reverse()
```

## Loop
```python
for city in cities:
    print(city)
```
