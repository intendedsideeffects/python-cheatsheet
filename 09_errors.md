# Errors

Read the **last line of the traceback first**. It usually contains the error type and message.

## Common exceptions
```text
SyntaxError       invalid Python syntax
NameError         variable/name does not exist
TypeError         operation used with wrong type
ValueError        correct type, invalid value
KeyError          dictionary key does not exist
IndexError        sequence index is out of range
FileNotFoundError file/path does not exist
```

## try / except
```python
try:
    number = int(user_input)
except ValueError:
    print("Please enter a number")
```

During practice, avoid catching errors too early — the traceback is useful information.
