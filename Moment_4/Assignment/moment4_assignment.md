# Programming 1 – Moment 4: Assignment

## 📝 Assignment Title
**Function-Based Calculator**

---

## 🎯 Goal
Create a calculator program that uses functions for different operations.

---

## 📋 Instructions

Write a Python program that:

1. Defines the following functions:
   - `add(x, y)` → returns the sum
   - `subtract(x, y)` → returns the difference
   - `multiply(x, y)` → returns the product
   - `divide(x, y)` → returns the quotient

2. Shows this menu in a loop:

```
==== CALCULATOR ====
1. Add
2. Subtract
3. Multiply
4. Divide
5. Quit
```

3. Asks the user to:
   - Choose an option (1–5)
   - Enter two numbers (for options 1–4)
   - Call the correct function and display the result

4. Ends the program if the user chooses option 5.

---

## 💡 Tips

- Use `while True:` and `break` to handle the menu loop
- Use `float()` or `int()` to convert number input
- Handle division by zero in the `divide` function

---

## 🧪 Example Run

```
==== CALCULATOR ====
1. Add
2. Subtract
3. Multiply
4. Divide
5. Quit
Choose an option: 1
Enter first number: 10
Enter second number: 3
Result: 13
```

---

## 🧩 Bonus Challenge (Optional)

- Add more operations like power (`x ** y`) or remainder (`x % y`)
- Handle invalid menu choices with an error message
- Ask if the user wants to continue or quit after each operation

---

## ✅ Submission

If you're working in a course platform:
- Upload your `.py` file with the assignment code
- Make sure your program runs without errors

If you're in class:
- Show your program to the teacher
- Be ready to explain how your code works
