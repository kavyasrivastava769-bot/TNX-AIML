# Track B — Day 5 Worksheet — Iterators, generators, decorators

**Name:** ______________________________  **GitHub handle:** ______________________________
**Track:** Track B (Advanced Python)  **Day:** 5  **Date:** Friday 16 Oct 2026

> Fill in the gaps. Run every program and paste the **real** output.

---

## Question 1 — A generator

Write a generator `countdown(n)` that `yield`s numbers from `n` down to `1`. Consume it with a `for`
loop.

**Your code:**

```python
# write your program here


```

**Output (n = 5):**

```
_______________________________________________________________________________
```

**What is the difference between this and returning a list of the same numbers?**
_______________________________________________________________________________

---

## Question 2 — A timing decorator

Write a decorator `timer` that prints how long the decorated function took (use `time.perf_counter()`).
Apply it to a function that sums the numbers 1 to 1,000,000.

**Your code:**

```python
# write your program here


```

**Output:**

```
_______________________________________________________________________________
```

---

## Question 3 — Case study: streaming a large file

Write a generator that yields one line at a time from a text file, and use it to count lines and the
number of characters **without** reading the whole file into memory.

**Your code:**

```python
# write your program here


```

**Output:**

```
_______________________________________________________________________________
```

**Why does a generator use far less memory than `f.readlines()` on a large file?**
_______________________________________________________________________________
