# Track B — Day 4 Worksheet — Comprehensions & lambdas

**Name:** Kavya Srivastava  **GitHub handle:** https://github.com/kavyasrivastava769-bot
**Track:** Track B (Advanced Python)  **Day:** 4  **Date:** Thursday 15 Oct 2026

> Fill in the gaps. Run every program and paste the **real** output.

---

## Question 1 — List comprehension

Given `nums = [1, 2, 3, 4, 5, 6, 7, 8]`, write **one comprehension** that produces the squares of only
the **even** numbers.

**Your code:**

```python
nums = [1, 2, 3, 4, 5, 6, 7, 8]
# write your program here
squares = [n**2 for n in nums if n % 2 == 0]
print(squares)

```

**Output:**

```
[4, 16, 36, 64]
```

**Rewrite the same thing as a `for` loop below. Which version do you find clearer, and why?**
__
nums = [1, 2, 3, 4, 5, 6, 7, 8]
squares = []

for n in nums:
    if n % 2 == 0:
        squares.append(n**2)

print(squares)
---

## Question 2 — Dict comprehension and lambdas

1. Build a dict of `number → number ** 2` for 1 to 5 using a dict comprehension.
2. Use `filter` with a **lambda** to keep only the values greater than 10.

**Your code:**

```python
# write your program here

squares = {n: n**2 for n in range(1, 6)}
print(squares)

# 2. Use filter with a lambda to keep values greater than 10
result = list(filter(lambda x: x > 10, squares.values()))
print(result)


```

**Output:**

```
{1: 1, 2: 4, 3: 9, 4: 16, 5: 25}
[16, 25]
```

---

## Question 3 — Case study: word frequency

Given the sentence below, build a dictionary of word → count in **comprehension style** (you may use
`set()` and `count()`).

```python
sentence = "the quick brown fox jumps over the lazy dog the fox"
```

**Your code:**

```python
sentence = "the quick brown fox jumps over the lazy dog the fox"
# write your program here

word_count = {word: sentence.split().count(word) for word in set(sentence.split())}

print(word_count)

```

**Output:**

```
{'the': 2, 'quick': 1, 'brown': 1, 'fox': 2, 'jumps': 1, 'over': 1, 'lazy': 1, 'dog': 1}
```

**What trade-off is there between a one-line comprehension and a plain loop for this task?**

A one-line comprehension makes the code shorter and more concise, but it can be harder to read and understand. A plain `for` loop takes more lines, but each step is clear and easier to debug. For this task, comprehension is convenient for short code, while a loop is better if we want to make the logic easier to follow.