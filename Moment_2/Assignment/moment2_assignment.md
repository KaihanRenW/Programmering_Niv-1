# Programming 1 – Moment 2: Assignment

## 📝 Assignment Title
**Decision Maker Program**

---

## 🎯 Goal
Create a program that uses `if`, `elif`, and `else` to make decisions based on user input.

---

## 📋 Instructions

Write a Python program that:

1. Asks the user for their age.
2. Asks the user if they have a driver's license (`yes` or `no`).
3. Based on the answers, prints one of the following messages:

   - If the user is 18 or older and has a license:  
     ➜ “You can drive a car.”

   - If the user is 18 or older but has no license:  
     ➜ “You are old enough but need a license.”

   - If the user is under 18:  
     ➜ “You are too young to drive.”

---

## 💡 Tips

- Use `input()` to ask questions.
- Convert the age to an integer using `int()`.
- Use `.lower()` to handle input like `Yes`, `YES`, or `yes`.

```python
answer = input("Do you have a license? ").lower()
```

---

## 🧪 Example Run

```
How old are you? 20
Do you have a license? yes
You can drive a car.
```

```
How old are you? 20
Do you have a license? no
You are old enough but need a license.
```

```
How old are you? 15
Do you have a license? no
You are too young to drive.
```

---

## 🧩 Bonus Challenge (Optional)

- Add a question asking which country the user lives in.
- If they live in Sweden and are at least 15 years old, print: “You can drive a moped in Sweden.”

---

## ✅ Submission

If you're working in a course platform:
- Upload your `.py` file with the assignment code
- Make sure your program runs without errors

If you're in class:
- Show your program to the teacher
- Be ready to explain how your code works
