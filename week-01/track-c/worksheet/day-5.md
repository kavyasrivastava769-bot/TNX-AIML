# Track C — Day 5 Worksheet — EDA & data cleaning

**Name:** ______________________________  **GitHub handle:** ______________________________
**Track:** Track C (ML Fundamentals)  **Day:** 5  **Date:** Friday 16 Oct 2026

**Video:** [ML Part 1 — Foundation](https://youtu.be/1L420xXpDTg) · 25:20 – 42:30

> Fill in the gaps. Run every snippet on a real CSV and paste the output.

---

## Question 1 — The ML workflow

List the stages of building a machine learning model, in order, in one line each.

1. ____________________________________________________________________________
2. ____________________________________________________________________________
3. ____________________________________________________________________________
4. ____________________________________________________________________________
5. ____________________________________________________________________________
6. ____________________________________________________________________________

**Which stage is usually the most time-consuming, and why?**
_______________________________________________________________________________

---

## Question 2 — Run EDA on a real CSV

Load a CSV and print: its shape, `info()`, the count of missing values per column, the number of
duplicate rows, and `describe()` for the numeric columns.

**Your code:**

```python
import pandas as pd
# write your program here


```

**Output:**

```
_______________________________________________________________________________
_______________________________________________________________________________
```

---

## Question 3 — Case study: clean this dataset

Below is a messy table. List **every** problem you can spot, then write the pandas steps you would use
to fix each one.

| id | name | age | city | salary |
|---|---|---|---|---|
| 1 | Asha | 28 | Delhi | 50000 |
| 2 | Ravi | | Mumbai | 62000 |
| 2 | Ravi | | Mumbai | 62000 |
| 4 | Neha | twenty | Pune | |
| 5 | Amit | 35 | Delhi | 48000 |

**Problems I found:**
1. ____________________________________________________________________________
2. ____________________________________________________________________________
3. ____________________________________________________________________________
4. ____________________________________________________________________________

**Pandas steps to fix them:**

```python
# write your fix steps here


```
