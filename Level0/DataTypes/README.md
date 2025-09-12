# 🐍 Python Data Types

Python is a dynamically typed language, meaning you don’t need to declare the type of a variable explicitly. The interpreter infers the type at runtime.

---

## 🔹 Basic Data Types

### `int` – Integer
Represents whole numbers.

```python
x = 42
```

### `float` – Floating Point Number
Represents decimal numbers.
```python
pi = 3.14159
```

### `str` – String
Represents sequences of characters.
```python
name = "Alice"
```

### `bool` – Boolean
Represents truth values: True or False.
```python
is_valid = True
```
---
## 🔸 Collection Data Types
### `list` – Ordered, Mutable Collection

```python
fruits = ["apple", "banana", "cherry"]
```
### `tuple` – Ordered, Immutable Collection
Similar to lists but cannot be modified.
```python
coordinates = (10.0, 20.0)
```

### `set` – Unordered, Unique Items
Stores unique values and removes duplicates automatically.
```python
colors = {"red", "green", "blue"}
```

### `dict` – Key-Value Pairs
Stores data in key-value format.
```python
person = {"name": "Bob", "age": 25}
```
---
## 🔹 Special Data Type
`NoneType`
Represents the absence of a value.

```python
result = None
```
---

## 🧪 Type Checking
Use the `type()` function to check the data type of a variable:

```python
print(type(x))        # <class 'int'>
print(type(fruits))   # <class 'list'>
```

Use `isinstance()` to verify if a variable is of a specific type:
```python
isinstance(x, int)    # True
```
---

## 📊 Summary Table

|Data|Type|Example Description|
|----|------|-----------------|
|int|x = 5|Whole numbers|
|float|pi = 3.14|Decimal numbers|
|str|"hello"|Text data|
|bool|True / False|Logical values|
|list|[1, 2, 3]|Ordered, mutable collection|
|tuple|(1, 2)|Ordered, immutable collection|
|set|{1, 2, 3}|Unordered, unique items|
|dict|{"a": 1}|Key-value pairs|
|NoneType|None|Represents no value|
---

## 🚀 Notes
* Python automatically assigns types at runtime.
* You can convert between types using functions like int(), str(), float(), etc.
* Collections can be nested and combined for complex data structures.