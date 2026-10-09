# Track B — Day 3 Worksheet — OOP: inheritance & polymorphism

**Name:** ______________________________  **GitHub handle:** ______________________________
**Track:** Track B (Advanced Python)  **Day:** 3  **Date:** Wednesday 14 Oct 2026

> Fill in the gaps. Run every program and paste the **real** output.

---

## Question 1 — Inheritance

Write a base class `Shape` with a method `area()` that returns `0`, and subclasses `Circle(radius)` and
`Rectangle(width, height)` that override `area()`. Use `super().__init__()` where useful.

**Your code:**

```python
# write your program here


```

**Output (circle r=3, rectangle 4x5):**

```
_______________________________________________________________________________
```

---

## Question 2 — Polymorphism

Create a list holding one `Circle` and one `Rectangle` and loop over it printing each `area()`. Explain
in one line what makes this work.

**Your code:**

```python
# write your program here


```

**Why does the loop not need to know which class each object is?**
_______________________________________________________________________________
_______________________________________________________________________________

---

## Question 3 — Case study: a safe bank account

Write a `BankAccount` class where the balance is **private** (name it `_balance`). Provide `deposit()`
and `withdraw()` methods; `withdraw()` must refuse amounts larger than the balance.

**Your code:**

```python
# write your program here


```

**Output (deposit 1000, withdraw 300, withdraw 5000):**

```
_______________________________________________________________________________
```

**Why is it safer to force callers to use `withdraw()` instead of editing `_balance` directly?**
_______________________________________________________________________________
