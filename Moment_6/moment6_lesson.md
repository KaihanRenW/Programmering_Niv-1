# Programming 1 – Moment 6: File Handling and Final Practice

## 🕐 Lesson Duration
**6 hours**

---

## 🎯 Lesson Goals
By the end of this lesson, you should be able to:

- Open, read, and write to files using Python
- Understand how to store data persistently
- Combine everything you've learned in larger programs

---

## 📄 Why Work with Files?

When your program ends, all data in variables is lost.  
To save data permanently, we use **files**.

Python can:
- Read from text files
- Write new data to files
- Append data without deleting what's already there

---

## 📖 Reading a File

```python
file = open("data.txt", "r")
content = file.read()
print(content)
file.close()
```

### Tip: Use `with` to auto-close files:
```python
with open("data.txt", "r") as file:
    content = file.read()
    print(content)
```

---

## ✏️ Writing to a File

This **overwrites** the file:
```python
with open("output.txt", "w") as file:
    file.write("Hello, file!")
```

---

## ➕ Appending to a File

This **adds** to the end of the file:
```python
with open("output.txt", "a") as file:
    file.write("\nAnother line")
```

---

## 🧪 Reading Line by Line

```python
with open("data.txt", "r") as file:
    for line in file:
        print("Line:", line.strip())
```

---

## ⚠️ File Paths

If your file is not in the same folder, use a full or relative path:

```python
with open("folder/data.txt") as file:
    ...
```

---

## 🧱 Good Practices

- Always close files (or use `with`)
- Use `.strip()` to clean newlines from lines
- Catch errors using `try` / `except` (optional)

---

## 🧪 Example Program: Log User Input

```python
with open("log.txt", "a") as file:
    name = input("Enter your name: ")
    file.write(name + "\n")
```

---

## 🧩 Summary

| Concept         | Description                              |
|------------------|------------------------------------------|
| `open()`         | Opens a file                             |
| `"r", "w", "a"`  | Read, write, append modes                |
| `read()`         | Reads the whole file                     |
| `write()`        | Writes (overwrites) to file              |
| `append()`       | Adds data to end of file                 |
| `with`           | Best way to work with files safely       |

---

## 📌 Central Content Covered (Skolverket)

- File input and output
- Saving and loading persistent data
- Applying programming skills in larger tasks

---

## ✅ Next Step
Continue with the practical exercises in the file `moment6_exercises.md`.
