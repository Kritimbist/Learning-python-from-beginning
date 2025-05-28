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


### ✅ Variables
- Variables store data for later use.
- Syntax: `variable_name = value`

```python
name = "Alice"
age = 25
height = 5.6
✅ Arithmetic Operators
Operator	Description	Example	Output
+	Addition	10 + 5	15
-	Subtraction	10 - 5	5
*	Multiplication	10 * 5	50
/	Division	10 / 5	2.0
//	Floor Division	10 // 3	3
%	Modulus (remainder)	10 % 3	1
**	Exponentiation	2 ** 3	8

✅ Comparison Operators
python
Copy
Edit
a = 10
b = 5

print(a > b)   # True
print(a == b)  # False
print(a != b)  # True
✅ User Input
python
Copy
Edit
name = input("Enter your name: ")
print("Hello,", name)
🧠 Note: input() always returns a string. Use int() or float() to convert it if needed.

python
Copy
Edit
age = int(input("Enter your age: "))
print("Next year you will be", age + 1)
