# Python Basics: Escape Sequences, Raw & Formatted Strings, and Variables & Data Types

## 1. Escape Sequences
Escape sequences are special character combinations in strings that perform specific formatting actions.

### Common Escape Sequences in Python:
| Escape Sequence | Meaning |
|----------------|---------|
| `\n` | New line |
| `\t` | Tab space |
| `\\` | Backslash (`\`) |
| `\"` | Double quote (`"`) |
| `\'` | Single quote (`'`) |
| `\r` | Carriage return |
| `\b` | Backspace |
| `\f` | Form feed |
| `\v` | Vertical tab |

### Example:
```python
print("Hello\nWorld")  # Output: Hello (new line) World
print("Name:\tJohn")   # Output: Name:    John
```

### Link: https://youtu.be/4rBPrJfF-GM?si=7-sIWQTcWXyj3jEY

---

## 2. Raw & Formatted Strings
### a) Raw Strings (`r` or `R` prefix)
Raw strings treat backslashes (`\`) as literal characters, preventing escape sequence interpretation.

#### Example:
```python
print(r"C:\Users\Sagar\Documents")  # Output: C:\Users\Sagar\Documents
```

### b) Formatted Strings (f-strings)
Introduced in Python 3.6, f-strings allow embedding expressions inside string literals using `{}`.

#### Example:
```python
name = "Sagar"
age = 25
print(f"My name is {name} and I am {age} years old.")
# Output: My name is Sagar and I am 25 years old.
```

### Link: https://youtu.be/IH284BmdME4?si=xfiagQ37yM-CbOfW

---

## 3. Variables & Data Types
### a) Variables in Python
Variables store data and do not require explicit type declaration.

#### Example:
```python
x = 10        # Integer
name = "Sagar"  # String
is_active = True  # Boolean
```

### b) Data Types in Python
Python has several built-in data types:

| Data Type | Example |
|-----------|---------|
| Integer (`int`) | `x = 10` |
| Floating-point (`float`) | `y = 3.14` |
| String (`str`) | `name = "John"` |
| Boolean (`bool`) | `is_active = True` |
| List (`list`) | `fruits = ["apple", "banana", "cherry"]` |
| Tuple (`tuple`) | `coordinates = (10, 20)` |
| Dictionary (`dict`) | `person = {"name": "John", "age": 25}` |
| Set (`set`) | `unique_numbers = {1, 2, 3, 4}` |
| NoneType (`None`) | `value = None` |

#### Example:
```python
# Checking types
x = 5
print(type(x))  # Output: <class 'int'>
```

### Link: https://youtu.be/LKFrQXaoSMQ?si=jrbdo523BHF-MTc4

---

### Summary:
- **Escape sequences** allow special formatting in strings.
- **Raw strings** treat backslashes as normal characters.
- **Formatted strings (f-strings)** allow embedding variables in strings.
- **Python variables** do not require explicit declaration.
- **Python has multiple built-in data types** such as `int`, `float`, `str`, `bool`, `list`, etc.


