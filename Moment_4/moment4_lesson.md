# Programming 1 – Moment 4: Functions and Modular Code

---

## 🎯 Lesson Goals
By the end of this lesson, you should be able to:

- Understand what a function is and why it is useful
- Write and call your own functions in Python
- Use parameters and return values
- Structure your code into reusable parts

---

## 🧠 What is a Function?

A **function** is a block of code that performs a specific task. You can run (or “call”) the function whenever you need that task to be done.

Using functions helps you:
- Avoid repeating code
- Make your programs easier to read
- Fix bugs more easily

---

## 🧪 Defining and Calling a Function

### Basic Syntax
```python
def greet():
    print("Hello!")
```

### Call the function:
```python
greet()
```

---

## 🧾 Parameters and Arguments

You can pass information into functions using **parameters**.

### Example:
```python
def greet(name):
    print("Hello,", name)

greet("Alice")
```

---

## 🔁 Return Values

Functions can return a value using the `return` keyword.

### Example:
```python
def add(a, b):
    return a + b

result = add(5, 3)
print(result)
```

---

## 🧱 Function Structure

```python
def function_name(parameters):
    # code block
    return value  # optional
```

### Example:
```python
def is_even(number):
    if number % 2 == 0:
        return True
    else:
        return False
```

---

## 🧪 Example Program

### A calculator using functions
```python
def add(x, y):
    return x + y

def subtract(x, y):
    return x - y

a = int(input("Enter first number: "))
b = int(input("Enter second number: "))

print("Sum:", add(a, b))
print("Difference:", subtract(a, b))
```

---

## 🧩 Summary

| Concept       | Description                                 |
|---------------|---------------------------------------------|
| Function      | Named block of code you can call repeatedly |
| Parameter     | Input to a function                         |
| Argument      | The actual value passed to a function       |
| Return value  | A result that the function gives back       |

---

## 📌 Central Content Covered (Skolverket)

- Defining and using functions
- Passing arguments and returning values
- Structuring code for reuse and clarity

---

## ✅ Next Step
Continue with the practical exercises in the file `moment4_exercises.md`.
