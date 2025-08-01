# Programming 1 – Moment 5: Lists and Collections

## 🕐 Lesson Duration
**6 hours**

---

## 🎯 Lesson Goals
By the end of this lesson, you should be able to:

- Understand what a list is in Python
- Create, read, and update lists
- Loop through lists using `for`
- Use basic list functions and methods
- Store and manage collections of data

---

## 📦 What is a List?

A **list** is a collection of values stored in a single variable.

You can store:
- Numbers
- Strings
- Even other lists!

### Example:
```python
fruits = ["apple", "banana", "cherry"]
```

---

## 🔢 Accessing List Items

You can access items using **indexes** (starting from 0).

```python
print(fruits[0])  # apple
print(fruits[2])  # cherry
```

---

## ✏️ Changing List Values

You can change an item by assigning a new value at a specific index:

```python
fruits[1] = "orange"
```

---

## ➕ Adding and Removing Items

### Add an item:
```python
fruits.append("kiwi")
```

### Remove an item:
```python
fruits.remove("banana")
```

---

## 🔁 Looping Through a List

```python
for fruit in fruits:
    print(fruit)
```

You can also use indexes:

```python
for i in range(len(fruits)):
    print(i, fruits[i])
```

---

## 🔍 Useful List Functions

| Function/Method       | Description                        |
|------------------------|------------------------------------|
| `len(list)`            | Number of items in the list        |
| `append(item)`         | Add item to the end                |
| `remove(item)`         | Remove the first matching item     |
| `pop(index)`           | Remove item at position            |
| `sort()`               | Sort the list (ascending)          |
| `in`                   | Check if an item is in the list    |

---

## 🧪 Example Program: Student Names

```python
students = []

for i in range(3):
    name = input("Enter student name: ")
    students.append(name)

print("List of students:")
for name in students:
    print("-", name)
```

---

## 🧩 Summary

| Concept         | Description                                  |
|------------------|----------------------------------------------|
| List             | A collection of values                      |
| Index            | Position of an item in the list (starting at 0) |
| Loop through list| Process each item using `for`               |
| Modify list      | Add/remove/update elements                  |

---

## 📌 Central Content Covered (Skolverket)

- Storing multiple values in collections (lists)
- Processing collections using loops
- Modifying, adding, removing items in a list

---

## ✅ Next Step
Continue with the practical exercises in the file `moment5_exercises.md`.
