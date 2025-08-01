# Programming 1 – Moment 1: Introduction to Programming with Python

## 🕐 Lesson Duration
**6 hours**

---

## 🎯 Lesson Goals
By the end of this lesson, you should be able to:

- Understand what programming is and why it's used
- Read and write simple pseudocode
- Use variables in Python
- Understand data types
- Perform mathematical calculations
- Write programs that use input and display output

---

## 🧠 What is Programming?

Programming is the art of instructing a computer to perform tasks. Instead of clicking around with a mouse, you write **code** – a set of instructions in a language that the computer can understand.

### Examples of programming usage:
- Mobile apps
- Games
- Websites
- Software for companies, schools, and hospitals

### Common programming languages:
- Python (we’ll use this!)
- JavaScript
- C#
- Java

---

## 🧾 Pseudocode – Plan Before You Code

**Pseudocode** is a way to write down a solution using simple words before writing real code.

### Example:

```
Ask the user for two numbers
Add the numbers
Print the result
```

This helps you think logically without worrying about programming language rules.

---

## 🧬 Data Types in Python

In Python, **data types** tell the computer what kind of information you are working with. Here are the most common ones for beginners:

| Data Type | Example        | Description                        |
|-----------|----------------|------------------------------------|
| `str`     | `"Hello"`      | Text (a "string")                  |
| `int`     | `42`           | Whole number (integer)             |
| `float`   | `3.14`         | Decimal number (floating point)    |
| `bool`    | `True` / `False` | Yes/No, On/Off (Boolean)         |

To convert between types:
```python
age = int("16")    # string to integer
text = str(42)     # integer to string
```

---

## 🧮 Variables – Storing Information

A **variable** is like a box where you can store a value, such as a number or a name.

### Python syntax:
```python
name = "Anna"
age = 16
```

Here we have two variables:
- `name` contains the text `"Anna"`
- `age` contains the number `16`

---

## ➕ Math Operators

Python can do calculations just like a calculator.

| Operator | Example    | Result |
|----------|------------|--------|
| `+`      | `5 + 2`    | `7`    |
| `-`      | `5 - 2`    | `3`    |
| `*`      | `5 * 2`    | `10`   |
| `/`      | `5 / 2`    | `2.5`  |
| `**`     | `5 ** 2`   | `25`   |
| `//`     | `5 // 2`   | `2`    |
| `%`      | `5 % 2`    | `1`    |

---

## ⌨️ User Input

Use the `input()` function to let the user type something.

### Example:
```python
name = input("What is your name? ")
print("Hello", name)
```

> `input()` always returns a string. Use `int()` or `float()` to convert it to a number if needed.

---

## 🖨️ Output – Print to Screen

Use `print()` to show text or values on the screen.

### Example:
```python
print("Hello world!")
```

You can also print multiple things:
```python
name = "Sara"
print("Hello", name)
```

---

## 🧪 Example Program

### Program 1: Simple Calculator
```python
num1 = int(input("Enter the first number: "))
num2 = int(input("Enter the second number: "))
sum = num1 + num2
print("The sum is:", sum)
```

---

## 🧩 Summary

| Concept     | Explanation                                  |
|-------------|----------------------------------------------|
| Programming | Writing instructions for a computer to follow|
| Pseudocode  | Planning code using plain language           |
| Data Type   | Type of value: text, number, etc.            |
| Variable    | A place to store information                 |
| Operator    | Symbols used for math                        |
| input()     | User input                                   |
| print()     | Display something on the screen              |

---

## 📌 Central Content Covered (Skolverket)

- Basics and use of programming
- Planning with pseudocode
- Data types and variables
- Operators and expressions
- User interaction (input/output)

---

## ✅ Next Step
Continue with the practical exercises in the file `moment1_exercises.md`.
