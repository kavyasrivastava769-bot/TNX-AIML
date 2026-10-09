# Track B — Day 1 Worksheet — Exception handling + file handling

**Name:** ______________________________  **GitHub handle:** ______________________________
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
# write your program here


```

**What exception type do you catch, and why that one?**
_______________________________________________________________________________

---

## Question 2 — Read a file safely

Write `reader.py` that opens `notes.txt`, prints each line, and prints `File not found` if it does not
exist — **without** the program crashing. Use `with`.

**Your code:**

```python
# write your program here


```

**Output when the file is missing:**

```
_______________________________________________________________________________
```

---

## Question 3 — Case study: robust CSV reader

You are given `marks.csv`, but one row may have a missing value. Write a function that:

1. reads the file,
2. skips and reports any row that cannot be converted to numbers,
3. returns the average of the valid rows.

**Your code:**

```python
# write your program here


```

**Why is `try` / `except` better than checking every value with `if` here?**
_______________________________________________________________________________
_______________________________________________________________________________
