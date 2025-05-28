DAY 001 : DATA TYPES IN PYTHON
---

## 📦 What is a Data Type?

A **data type** defines the kind of value a variable holds and what operations you can perform with it.  

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
```
float – Decimal Number
```python
pi = 3.14
print(pi, type(pi))  # Output: 3.14 <class 'float'>
```
complex – Complex Number
```python
z = 2 + 3j
print(z, type(z))  # Output: (2+3j) <class 'complex'>
🔤 Text Type
str – String (Text)
```
string:(Text)
```python

name = "Alice"
print(name, type(name))  # Output: Alice <class 'str'>
```
✅ Boolean Type
bool – True or False

```python
is_active = True
print(is_active, type(is_active))  # Output: True <class 'bool'>
```
📚 Sequence Types
list – Ordered, Changeable Collection
```python

fruits = ["apple", "banana", "cherry"]
print(fruits, type(fruits))  # Output: ['apple', 'banana', 'cherry'] <class 'list'>
tuple – Ordered, Unchangeable Collection
```
```python

colors = ("red", "green", "blue")
print(colors, type(colors))  # Output: ('red', 'green', 'blue') <class 'tuple'>
range – Sequence of Numbers
```
```python

nums = range(5)
print(list(nums), type(nums))  # Output: [0, 1, 2, 3, 4] <class 'range'>
```
🔑 Mapping Type
dict – Key-Value Pairs
```python

person = {"name": "Alice", "age": 25}
print(person, type(person))  # Output: {'name': 'Alice', 'age': 25} <class 'dict'>
```
🪣 Set Types
set – Unordered, Unique Items
```python

unique_numbers = {1, 2, 3, 1}
print(unique_numbers, type(unique_numbers))  # Output: {1, 2, 3} <class 'set'>
```
frozenset – Immutable Set
```python

frozen = frozenset([1, 2, 3])
print(frozen, type(frozen))  # Output: frozenset({1, 2, 3}) <class 'frozenset'>
```
🕳️ None Type
NoneType – Represents No Value
```python

empty = None
print(empty, type(empty))  # Output: None <class 'NoneType'>
```
# 📅 Day 2 – Variables, Operators, and Input/Output in Python

---


## ✅ Variables
- Variables store data for later use.
- Syntax: `variable_name = value`

```python
name = "Alice"// string variable
age = 25 // integer varible
height = 5.6// float variable
```
## ✅ Operators
In Python, operators are special symbols that perform operations on variables and values. They are the building blocks for performing calculations, comparisons, logical decisions, and more.
 ## Types of Operators
 ---
 - arithmetic-operators
- comparison-operators
- assignment-operators
- logical-operators
- bitwise-operators
- membership operators
- identity-operators

 ### Arithmetic operators
Used to perform mathematical operations.

```python
a = 10
b = 3

print(a + b)   # 13 → Addition
print(a - b)   # 7  → Subtraction
print(a * b)   # 30 → Multiplication
print(a / b)   # 3.333... → Division
print(a // b)  # 3  → Floor Division
print(a % b)   # 1  → Modulus (remainder)
print(a ** b)  # 1000 → Exponent (power)
```
### Comparison operators
Compare two values and return True or False.
```python
x = 5
y = 10

print(x == y)  # False → Equal to
print(x != y)  # True  → Not equal to
print(x > y)   # False → Greater than
print(x < y)   # True  → Less than
print(x >= y)  # False → Greater than or equal to
print(x <= y)  # True  → Less than or equal to
```
### Assignment Operators
Used to assign values and perform operations in one line.
```python
x = 5
x += 2   # x = x + 2 → 7
x -= 1   # x = x - 1 → 6
x *= 3   # x = x * 3 → 18
x /= 2   # x = x / 2 → 9.0
x //= 2  # x = x // 2 → 4.0
x %= 3   # x = x % 3 → 1.0
x **= 2  # x = x ** 2 → 1.0
print(x)
```
###  Logical Operators
Used to combine conditional statements.
```python
a = True
b = False

print(a and b)  # False → Both must be true
print(a or b)   # True  → At least one is true
print(not a)    # False → Inverts the value
```
### Bitwise Operators
Operate on bits (binary values).
```python
a = 5   # 0101
b = 3   # 0011

print(a & b)  # 1 → AND
print(a | b)  # 7 → OR
print(a ^ b)  # 6 → XOR
print(~a)     # -6 → NOT (inverts all bits)
print(a << 1) # 10 → Left shift
print(a >> 1) # 2  → Right shift
```
### Membership Operators
Test if a value exists in a sequence (like string, list, tuple, etc).
```python
name = "Python"

print("y" in name)     # True
print("z" not in name) # True
```
### Identity Operators
Compare the memory location of two objects.
```python
a = [1, 2, 3]
b = a
c = [1, 2, 3]

print(a is b)      # True  → Same object
print(a is c)      # False → Different objects
print(a is not c)  # True
```

## Simple Program combining all operators
```python
a = 10
b = 3

print(" Arithmetic Operators")
print("a + b =", a + b)   # 13
print("a - b =", a - b)   # 7
print("a * b =", a * b)   # 30
print("a / b =", a / b)   # 3.33...
print("a // b =", a // b) # 3
print("a % b =", a % b)   # 1
print("a ** b =", a ** b) # 1000
print()

#  Comparison Operators
print(" Comparison Operators")
print("a == b:", a == b)  # False
print("a != b:", a != b)  # True
print("a > b:", a > b)    # True
print("a < b:", a < b)    # False
print("a >= b:", a >= b)  # True
print("a <= b:", a <= b)  # False
print()

#  Assignment Operators
x = 5
print(" Assignment Operators")
x += 2   # x = x + 2
print("x += 2 →", x)
x *= 3   # x = x * 3
print("x *= 3 →", x)
print()

#  Logical Operators
is_sunny = True
have_umbrella = False
print(" Logical Operators")
print("is_sunny and have_umbrella:", is_sunny and have_umbrella)  # False
print("is_sunny or have_umbrella:", is_sunny or have_umbrella)    # True
print("not is_sunny:", not is_sunny)                               # False
print()

#  Bitwise Operators (just for demo)
print(" Bitwise Operators")
print("a & b =", a & b)   # 2
print("a | b =", a | b)   # 11
print()

#  Membership Operators
name = "Python"
print(" Membership Operators")
print("'y' in name:", 'y' in name)        # True
print("'a' not in name:", 'a' not in name) # True
print()

#  Identity Operators
list1 = [1, 2, 3]
list2 = list1
list3 = [1, 2, 3]
print(" Identity Operators")
print("list1 is list2:", list1 is list2)       # True
print("list1 is list3:", list1 is list3)       # False
print("list1 is not list3:", list1 is not list3) # True
```





