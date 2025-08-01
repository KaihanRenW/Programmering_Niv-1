# Programming 1 – Moment 6: Assignment

## 📝 Assignment Title
**To-Do List with File Storage**

---

## 🎯 Goal
Create a program that allows the user to manage a to-do list that is saved in a text file.

---

## 📋 Instructions

Write a Python program that:

1. Uses a file called `todo.txt` to save tasks.
2. Shows a menu in a loop:

```
==== TO-DO LIST ====
1. View tasks
2. Add task
3. Remove task
4. Quit
```

3. Implements the following features:
- **View tasks:** Read and print all lines from `todo.txt`
- **Add task:** Ask for a task and append it to the file
- **Remove task:** Ask for a task and remove it from the file (reload file contents, filter, and write back)

---

## 💡 Tips

- Use `with open(...)` for all file operations
- Read file into a list with `readlines()` and remove tasks using `.strip()`
- Write the list back using `w` mode and `write()` or `writelines()`

---

## 🧪 Example Run

```
==== TO-DO LIST ====
1. View tasks
2. Add task
3. Remove task
4. Quit
Choose option: 1
Tasks:
- Buy milk
- Call mom
```

---

## 🧩 Bonus Challenge (Optional)

- Add timestamps to tasks using `datetime`
- Sort the list alphabetically before showing
- Handle empty file gracefully

---

## ✅ Submission

If you're working in a course platform:
- Upload your `.py` file and `todo.txt` (if created manually)
- Make sure your program runs without errors

If you're in class:
- Show your program to the teacher
- Be ready to explain how file handling works in your solution
