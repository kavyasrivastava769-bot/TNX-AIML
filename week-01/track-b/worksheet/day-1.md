# Track B — Day 1 Worksheet — Exception handling + file handling

**Name:** Kavya Srivastava  **GitHub handle:** https://github.com/kavyasrivastava769-bot
**Track:** Track B (Advanced Python)  **Day:** 1  **Date:** Monday 12 Oct 2026

> Fill in the gaps. Run every program and paste the **real** output.

---

## Question 1 — Catch the crash

The snippet below crashes when the second number is `0`. Wrap it in `try` / `except` so it prints a
friendly message instead, and add a `finally` that prints `Done`.

```python
a = int(input("First number: "))
b = int(input("Second number: "))
print(a / b)
```

**Your code:**

```python

try:
    a = int(input("First number: "))
    b = int(input("Second number: "))
    print(a / b)
except ZeroDivisionError:
    print("Cannot divide by zero")
finally:
    print("Done")
```

    Output
    
First number: 10
Second number: 2
5.0
Done





**What exception type do you catch, and why that one?**
I found ZeroDivisonError as dividing a number by zero is not allowed .

---

## Question 2 — Read a file safely

Write `reader.py` that opens `notes.txt`, prints each line, and prints `File not found` if it does not
exist — **without** the program crashing. Use `with`.

**Your code:**

```python

try:
    with open("notes.txt", "r") as file:
        for line in file:
            print(line, end="")
except FileNotFoundError:
    print("File not found")


```
if notes.txt exists
Output
hello I am Kavya srivastava


**Output when the file is missing:**

```
File not found
```

---

## Question 3 — Case study: robust CSV reader

You are given `marks.csv`, but one row may have a missing value. Write a function that:

1. reads the file,
2. skips and reports any row that cannot be converted to numbers,
3. returns the average of the valid rows.

**Your code:**

```python

import csv

def calculate_average(filename):
    valid_marks = []

    with open(filename, "r", newline="") as file:
        reader = csv.reader(file)
        next(reader, None)

        for row in reader:
            try:
                marks = [float(value) for value in row]
                valid_marks.extend(marks)
            except ValueError:
                print(f"Skipping invalid row: {row}")

    if not valid_marks:
        return None

    return sum(valid_marks) / len(valid_marks)


try:
    average = calculate_average("marks.csv")
    if average is None:
        print("No valid marks found")
    else:
        print("Average:", average)
except FileNotFoundError:
    print("CSV file not found")


```
marks.csv

Name,Marks
Aman,80
Riya,90
Rahul,th
Priya,70

Output

Skipping invalid row: ['Rahul', 'th']
Average: 80.0


**Why is `try` / `except` better than checking every value with `if` here?**
`try`/`except` are better than `if` because it checks all the errors and invalid values instead of checking every possible value manually.
