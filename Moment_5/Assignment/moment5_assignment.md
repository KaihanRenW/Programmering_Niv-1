# Programming 1 – Moment 5: Assignment

## 📝 Assignment Title
**Simple Contact List Manager**

---

## 🎯 Goal
Create a Python program that allows the user to build and manage a list of contacts using lists.

---

## 📋 Instructions

Write a Python program that:

1. Creates an empty list called `contacts`
2. Repeats a menu until the user chooses to quit:

```
==== CONTACT LIST ====
1. Add a contact
2. Show all contacts
3. Search for a contact
4. Remove a contact
5. Quit
```

3. Implements the following features:
   - **Option 1:** Ask for a name and add it to the list
   - **Option 2:** Print all names in the list
   - **Option 3:** Ask for a name and check if it exists in the list
   - **Option 4:** Ask for a name and remove it if found
   - **Option 5:** End the program

---

## 💡 Tips

- Use a `while True:` loop for the menu
- Use `append()`, `in`, `remove()` and `print()` for list operations
- Use `break` to exit the loop when the user chooses to quit

---

## 🧪 Example Run

```
==== CONTACT LIST ====
1. Add a contact
2. Show all contacts
3. Search for a contact
4. Remove a contact
5. Quit
Choose an option: 1
Enter name: Alice

Choose an option: 2
Contacts:
- Alice
```

---

## 🧩 Bonus Challenge (Optional)

- Prevent duplicate names in the list
- Add a confirmation message when a name is added or removed
- Sort the contact list alphabetically before printing

---

## ✅ Submission

If you're working in a course platform:
- Upload your `.py` file with the assignment code
- Make sure your program runs without errors

If you're in class:
- Show your program to the teacher
- Be ready to explain how your code works
