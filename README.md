DAY 01 - DATA TYPE:

Data type define what kind of value a variable hold and what operation can be performed on it.
**Common Python Data Types:**
| Data Type  | Description                      | Example                   |
| ---------- | -------------------------------- | ------------------------- |
| `int`      | Integer (whole number)           | `5`, `-12`, `100`         |
| `float`    | Decimal (floating point number)  | `3.14`, `-0.5`            |
| `str`      | String (text)                    | `"hello"`, `'Python'`     |
| `bool`     | Boolean (True or False)          | `True`, `False`           |
| `list`     | Ordered, changeable collection   | `[1, 2, 3]`, `["a", "b"]` |
| `tuple`    | Ordered, unchangeable collection | `(1, 2, 3)`               |
| `dict`     | Key-value pairs                  | `{"name": "Alice"}`       |
| `set`      | Unordered, unique items          | `{1, 2, 3}`               |
| `NoneType` | Represents "nothing" or no value | `None`                    |


# 🐍 Python Data Types

Welcome to this mini-guide on **Data Types in Python**!  
Understanding data types is one of the most important steps in learning how to code in Python.

---

## 📦 What is a Data Type?

A **data type** defines the kind of value a variable holds and what operations you can perform with it.  
Think of it as a label that tells Python: "Hey, this is a number", or "This is a piece of text".

---

## 🧮 Built-in Data Types in Python

### 🔢 Numbers
| Type   | Description                  | Example      |
|--------|------------------------------|--------------|
| `int`  | Integer values               | `10`, `-3`   |
| `float`| Decimal values               | `3.14`, `-0.1`|
| `complex` | Complex numbers (rare)     | `2 + 3j`     |

---

### 🔤 Text
| Type   | Description                  | Example         |
|--------|------------------------------|-----------------|
| `str`  | String - sequence of characters | `"hello"`    |

---

### ✅ Boolean
| Type   | Description                  | Example   |
|--------|------------------------------|-----------|
| `bool` | Logical True or False        | `True`, `False` |

---

### 📚 Sequence Types
| Type   | Description                  | Example           |
|--------|------------------------------|-------------------|
| `list` | Ordered, changeable          | `[1, 2, 3]`       |
| `tuple`| Ordered, unchangeable        | `(4, 5, 6)`       |
| `range`| Sequence of numbers          | `range(5)`        |

---

### 🔑 Mapping Type
| Type   | Description                  | Example              |
|--------|------------------------------|----------------------|
| `dict` | Key-value pairs              | `{"name": "Alice"}` |

---

### 🪣 Set Types
| Type   | Description                  | Example         |
|--------|------------------------------|-----------------|
| `set`  | Unordered, unique items      | `{1, 2, 3}`     |
| `frozenset` | Immutable version of set | `frozenset([1,2])`|

---

### 🕳️ None Type
| Type        | Description                 | Example   |
|-------------|-----------------------------|-----------|
| `NoneType`  | Represents no value / null  | `None`    |

---

## 🧪 How to Check a Variable's Data Type

```python
x = 10
print(type(x))  # Output: <class 'int'>
