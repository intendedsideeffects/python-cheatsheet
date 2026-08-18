# Files

## Read a text file
```python
with open("notes.txt", "r", encoding="utf-8") as file:
    text = file.read()
```

## Write a text file
```python
with open("output.txt", "w", encoding="utf-8") as file:
    file.write("Hello")
```

## Read line by line
```python
with open("notes.txt", encoding="utf-8") as file:
    for line in file:
        print(line.strip())
```

Using `with` closes the file automatically.
