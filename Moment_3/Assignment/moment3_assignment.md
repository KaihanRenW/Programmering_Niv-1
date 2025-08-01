# Programming 1 – Moment 3: Assignment

## 📝 Assignment Title
**Loop-based Menu Program**

---

## 🎯 Goal
Create a program that uses loops and conditions to present a simple menu to the user and repeat actions until the user chooses to quit.

---

## 📋 Instructions

Write a Python program that:

1. Shows the following menu in a loop:

```
==== MENU ====
1. Say hello
2. Show numbers 1–5
3. Multiply two numbers
4. Quit
```

2. Asks the user to choose an option (1–4).
3. Based on the choice:
   - Option 1 → Print: "Hello!"
   - Option 2 → Use a `for` loop to print numbers 1 through 5
   - Option 3 → Ask the user for two numbers and print the result of multiplication
   - Option 4 → Exit the loop and print “Goodbye!”

---

## 💡 Tips

- Use a `while True:` loop to keep the menu running
- Use `input()` and `int()` to read menu choices
- Use `break` to exit the loop on option 4
- You can use `if`, `elif`, and `else` to handle each choice

---

## 🧪 Example Run

```
==== MENU ====
1. Say hello
2. Show numbers 1–5
3. Multiply two numbers
4. Quit
Choose an option: 1
Hello!

==== MENU ====
1. Say hello
2. Show numbers 1–5
3. Multiply two numbers
4. Quit
Choose an option: 2
1
2
3
4
5
...
```

---

## 🧩 Bonus Challenge (Optional)

- Add an option to display the multiplication table for a number from 1 to 10
- Handle invalid input by printing a message like: "Please choose 1, 2, 3, or 4"

---

## ✅ Submission

If you're working in a course platform:
- Upload your `.py` file with the assignment code
- Make sure your program runs without errors

If you're in class:
- Show your program to the teacher
- Be ready to explain how your code works
