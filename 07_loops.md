# Loops

## for loop
```python
cities = ["Berlin", "Paris", "London"]

for city in cities:
    print(city)
```

## range
```python
for number in range(5):
    print(number)  # 0 to 4

for number in range(1, 6):
    print(number)  # 1 to 5
```

## enumerate
```python
for index, city in enumerate(cities):
    print(index, city)
```

## while loop
```python
count = 0
while count < 3:
    print(count)
    count += 1
```

## Control flow
```python
break       # stop loop
continue    # skip current iteration
```
