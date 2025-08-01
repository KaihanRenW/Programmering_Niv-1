# Programming 1 – Moment 3: Loops and Repetition

## 🕐 Lesson Duration
**6 hours**

---

## 🎯 Lesson Goals
By the end of this lesson, you should be able to:

- Understand what loops are and why we use them
- Use `while` loops to repeat actions
- Use `for` loops to iterate over sequences
- Use `range()` to repeat code a specific number of times
- Combine loops with conditions to create useful programs

---

## 🔁 What is a Loop?

A **loop** allows your program to repeat actions without writing the same code over and over again.

There are two main types of loops in Python:
- `while` loop → repeats **as long as a condition is true**
- `for` loop → repeats **a specific number of times or over a list**

---

## 🌀 while Loop

The `while` loop repeats a block of code **as long as a condition is true**.

### Syntax:
```python
while condition:
    # code to repeat
```

### Example:
```python
count = 0
while count < 5:
    print("Count is", count)
    count += 1
```

> 🔁 This will print numbers 0 to 4.

Be careful! If the condition is always true, the loop runs forever. This is called an **infinite loop**.

---

## 🔢 for Loop and range()

A `for` loop is useful when you know **how many times** you want to repeat something.

### Example:
```python
for i in range(5):
    print("Loop number", i)
```

This prints:
```
Loop number 0
Loop number 1
Loop number 2
Loop number 3
Loop number 4
```

### `range(start, stop, step)`

You can control the range:
```python
for i in range(1, 11, 2):
    print(i)
```

This prints: 1, 3, 5, 7, 9

---

## 🧾 Using Loops with Input

You can combine loops with input to make interactive programs.

### Example: Ask until correct password
```python
password = ""

while password != "abc123":
    password = input("Enter password: ")

print("Access granted!")
```

---

## 🧪 Example Program: Multiplication Table

```python
number = int(input("Enter a number: "))

for i in range(1, 11):
    result = number * i
    print(number, "x", i, "=", result)
```

---

## 🧩 Summary

| Concept         | Description                                    |
|------------------|------------------------------------------------|
| `while` loop     | Repeats while a condition is true              |
| `for` loop       | Repeats over a range or list                   |
| `range()`        | Generates a sequence of numbers                |
| `break` / `continue` | Control the flow inside a loop (optional)  |

---

## 📌 Central Content Covered (Skolverket)

- Repetitive control structures (loops)
- Using conditions within loops
- Writing structured programs with repetition

---

## ✅ Next Step
Continue with the practical exercises in the file `moment3_exercises.md`.
