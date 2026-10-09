# Track C — Day 6 Worksheet — Preprocessing, feature engineering & selection

**Name:** ______________________________  **GitHub handle:** ______________________________
**Track:** Track C (ML Fundamentals)  **Day:** 6  **Date:** Saturday 17 Oct 2026

**Video:** [ML Part 1 — Foundation](https://youtu.be/1L420xXpDTg) · 42:30 – 1:01:42

> Fill in the gaps. Run every snippet and paste the **real** output.

---

## Question 1 — Encoding categorical columns

Given the column `city = ["Delhi", "Mumbai", "Pune", "Delhi"]`, encode it two ways: **label encoding**
and **one-hot encoding**. Print both results.

**Your code:**

```python
import pandas as pd
# write your program here


```

**Output:**

```
_______________________________________________________________________________
```

**When is one-hot encoding safer than label encoding, and why?**
_______________________________________________________________________________

---

## Question 2 — Scaling

Scale the column `[10, 20, 30, 40, 50]` two ways: **min-max** to the range 0–1, and **standardisation**
(mean 0, standard deviation 1). Print both.

**Your code:**

```python
# write your program here


```

**Output (min-max):**
```
_______________________________________________________________________________
```
**Output (standardised):**
```
_______________________________________________________________________________
```

**Why do many models need scaled inputs?**
_______________________________________________________________________________

---

## Question 3 — Case study: engineer and select features

Starting from the columns `date` (e.g. `2026-10-05`), `price`, and `quantity`, **engineer** at least
two new features (for example `month`, `day_of_week`, `total = price * quantity`) and then **select**
the features you would actually feed a model, with a one-line reason each.

**Your code:**

```python
import pandas as pd
df = pd.DataFrame({
    "date": ["2026-10-05", "2026-10-06"],
    "price": [100, 250],
    "quantity": [2, 1],
})
# write your program here


```

**Features I kept and why:**

| Feature | Keep? | Reason |
|---|---|---|
| | | |
| | | |
| | | |

**Feature selection reduces noise — explain that idea in one sentence:**
_______________________________________________________________________________
