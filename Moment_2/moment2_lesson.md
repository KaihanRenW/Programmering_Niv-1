# Programming 1 – Moment 2: Conditions and Control Structures

## 🎯 Lesson Goals
By the end of this lesson, you should be able to:

- Understand and use if-statements
- Compare values using comparison operators
- Use logical operators (`and`, `or`, `not`)
- Write programs that make decisions based on user input

---

## 🔁 What is a Control Structure?

Control structures allow your program to **make decisions** or **repeat actions**.

In this lesson, we’ll focus on **conditional statements**, which let the program choose what to do depending on different conditions.

---

## 🧪 if-statements – Making Decisions

The `if` statement is used to check a condition. If the condition is `True`, the block of code under it will run.

### Syntax:
```python
if condition:
    # code to run if condition is True
```

### Example:
```python
age = int(input("How old are you? "))
if age >= 18:
    print("You are an adult.")
```

---

## 📊 Comparison Operators

These operators are used to compare values:

| Operator | Meaning                  | Example      | Result     |
|----------|--------------------------|--------------|------------|
| `==`     | Equal to                 | `5 == 5`     | `True`     |
| `!=`     | Not equal to             | `5 != 3`     | `True`     |
| `>`      | Greater than             | `5 > 3`      | `True`     |
| `<`      | Less than                | `2 < 5`      | `True`     |
| `>=`     | Greater than or equal to | `5 >= 5`     | `True`     |
| `<=`     | Less than or equal to    | `3 <= 5`     | `True`     |

---

## 🤝 Logical Operators

You can combine conditions using logical operators:

| Operator | Meaning                     | Example                    | Result   |
|----------|-----------------------------|----------------------------|----------|
| `and`    | Both conditions must be true| `age > 12 and age < 20`    | True     |
| `or`     | At least one must be true   | `age < 13 or age > 65`     | True     |
| `not`    | Reverses the result         | `not (age > 18)`           | False    |

---

## 🧭 else and elif

You can add an `else` block for code that should run when the `if` condition is false.

```python
if age >= 18:
    print("Adult")
else:
    print("Minor")
```

You can also add more conditions using `elif` (short for “else if”):

```python
if age < 13:
    print("Child")
elif age < 18:
    print("Teenager")
else:
    print("Adult")
```

---

## 🧪 Example Program

### Voting eligibility checker
```python
age = int(input("Enter your age: "))

if age >= 18:
    print("You are allowed to vote.")
elif age >= 16:
    print("You may vote in some elections.")
else:
    print("You are too young to vote.")
```

---

## 🧩 Summary

| Concept           | Explanation                                  |
|-------------------|----------------------------------------------|
| if                | Runs code if a condition is true             |
| else              | Runs code if the condition is false          |
| elif              | Checks another condition if the first is false |
| Comparison        | Checks equality or size of values            |
| Logical operators | Combine or invert conditions                 |

---

## 📌 Central Content Covered (Skolverket)

- Control structures for branching: if, else, elif
- Logical expressions and conditions
- Programs that make decisions

---

## ✅ Next Step
Continue with the practical exercises in the file `moment2_exercises.md`.
