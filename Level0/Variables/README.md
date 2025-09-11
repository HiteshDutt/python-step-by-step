# 🐍 Python Variables: A Beginner's Guide

Variables are one of the most essential concepts in Python programming. They allow you to store and manipulate data throughout your code.

---

## 📘 What Is a Variable?

A **variable** is a name that refers to a value. It acts as a container for data that can change or be reused.

```python
message = "Hello, World!"
count = 10
price = 99.99
```

---

## 🧠 How to Assign Variables

Use the `=` operator to assign a value to a variable:

```python
name = "Alice"
age = 25
is_student = True
```

Python automatically detects the type of data you're assigning—no need to declare types explicitly.

---

## 🔢 Common Data Types

| Type        | Example             |
|-------------|---------------------|
| Integer     | `x = 42`            |
| Float       | `pi = 3.14159`      |
| String      | `greeting = "Hi"`   |
| Boolean     | `is_valid = False`  |
| List        | `colors = ["red", "blue"]` |
| Dictionary  | `user = {"name": "Bob", "age": 30}` |

---

## 🧾 Naming Rules

- Must start with a letter or underscore (`_`)
- Cannot start with a number
- Can contain letters, numbers, and underscores
- Case-sensitive (`Name` and `name` are different)
- Avoid using Python keywords (like `class`, `def`, `if`)

✅ Good examples:
```python
user_name = "Charlie"
total_price = 250
```

❌ Bad examples:
```python
2name = "Invalid"
class = "Keyword"
```

---

## 🌍 Variable Scope

- **Global variables**: Defined outside functions, accessible everywhere.
- **Local variables**: Defined inside functions, accessible only within that function.

```python
x = 5  # Global

def show():
    y = 10  # Local
    print(x + y)
```

---

## 🔄 Reassigning Variables

Variables can be updated or reassigned:

```python
score = 100
score = score + 50  # Now score is 150
```

---

## 💡 Tips for Beginners

- Use descriptive names to make your code readable.
- Comment your code to explain the purpose of variables.
- Practice using different data types and observe how Python handles them.

---

## 🎉 Conclusion

Variables are the foundation of any Python program. Mastering them will help you write clean, efficient, and powerful code.

Happy coding!
