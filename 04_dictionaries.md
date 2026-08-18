# Dictionaries

Dictionaries store data as key-value pairs.

```python
person = {
    "name": "Janina",
    "city": "Berlin",
    "role": "Data Consultant"
}
```

## Access
```python
person["name"]
person.get("city")
```

## Add or change
```python
person["language"] = "Python"
person["city"] = "Hamburg"
```

## Remove
```python
del person["language"]
person.pop("city")
```

## Loop
```python
for key, value in person.items():
    print(key, value)
```

## Useful methods
```python
person.keys()
person.values()
person.items()
```
