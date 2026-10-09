# Track A — Python Basics: Week 1 Checklist

**Track A** is for members who know zero or minimal coding, or who want to brush up the basics.
Work through the checklist in order, one day at a time. Every day ends with a small hands-on
deliverable — watching alone is not the work. Flip each `- [ ]` to `- [x]` as you finish it, then
commit your changes in your own fork.

**Source video:** [Python Full Course for Beginners to Advanced (12 hours)](https://youtu.be/_aWbUudZ5Yo)
**Week:** Mon 12 Oct 2026 → Mon 19 Oct 2026 · **7 topic days** (Mon–Sun) + a review Monday.
**Goal by Monday 19 Oct:** write and run small Python programs up to **`if` / `elif` / `else`**.
**Scope this week:** watch the course from the start to the **end of the If-Else chapter (0:00 → 2:16:14)**.

> Each day's questions live in the matching file under [`worksheet/`](worksheet/README.md), e.g. Day 1
> questions are in [`worksheet/day-1.md`](worksheet/day-1.md).

---

## Day 1 — Monday 12 Oct 2026 — Setup + your first program

**Watch:** [0:00 – 15:32](https://youtu.be/_aWbUudZ5Yo?t=0)

- [ ] **Introduction & course overview** — `0:00` · what the course covers and how to follow it. Why it matters: you know the map before you start walking.
- [ ] **Python history & origin** — `2:13` · where Python came from and why it is used. Why it matters: context makes the design choices make sense.
- [ ] **How Python works internally** — `4:47` · interpreter vs compiler. Why it matters: explains why Python runs line by line.
- [ ] **Installation & VS Code setup** — `6:19` · install Python and set up VS Code (or use Colab). Why it matters: every topic this week runs on a real interpreter.
- **Deliverable:** a file `hello.py` that prints your name and a greeting.
- **Worksheet:** [Day 1](worksheet/day-1.md)

## Day 2 — Tuesday 13 Oct 2026 — Comments, variables, and data types

**Watch:** [15:32 – 34:28](https://youtu.be/_aWbUudZ5Yo?t=932)

- [ ] **Comments & variables** — `15:32` · writing clean comments, creating and naming variables. Why it matters: variables are how a program remembers data between steps.
- [ ] **Data types in Python** — `25:19` · `int`, `float`, `str`, `bool`, and `type()`. Why it matters: the type decides what operations are allowed.
- **Deliverable:** a script `profile.py` that stores your name, age, height, and student status in correctly typed variables and prints each with its type.
- **Worksheet:** [Day 2](worksheet/day-2.md)

## Day 3 — Wednesday 14 Oct 2026 — Strings & type conversion

**Watch:** [34:28 – 51:49](https://youtu.be/_aWbUudZ5Yo?t=2068)

- [ ] **Strings** — `34:28` · quotes, concatenation, indexing, and methods like `.upper()`, `.lower()`, `.strip()`. Why it matters: text is the most common data a beginner handles.
- [ ] **Type conversion** — `34:28` · `int()`, `float()`, `str()`, and f-strings. Why it matters: data almost always arrives as text and must be converted before it can be computed.
- **Deliverable:** a script `receipt.py` that builds a formatted multi-line receipt from fixed values using f-strings.
- **Worksheet:** [Day 3](worksheet/day-3.md)

## Day 4 — Thursday 15 Oct 2026 — Input & output

**Watch:** [51:49 – 59:11](https://youtu.be/_aWbUudZ5Yo?t=3109)

- [ ] **`input()`** — `51:49` · reading a value typed by the user. Why it matters: programs that only print fixed text are not very useful.
- [ ] **Formatted output** — `51:49` · `print()` with f-strings and separators. Why it matters: readable output is how you check your program is correct.
- [ ] **Converting input** — combining `input()` with `int()` / `float()`. Why it matters: `input()` always returns a string — this is the single most common beginner bug.
- **Deliverable:** a script `circle.py` that asks for a radius and prints the area and circumference of a circle.
- **Worksheet:** [Day 4](worksheet/day-4.md)

## Day 5 — Friday 16 Oct 2026 — Operators

**Watch:** [59:11 – 1:39:27](https://youtu.be/_aWbUudZ5Yo?t=3551)

- [ ] **Arithmetic operators** — `59:11` · `+ - * / // % **` and operator precedence. Why it matters: almost every computation is a sequence of these.
- [ ] **Comparison & logical operators** — `59:11` · `== != < > <= >=` with `and`, `or`, `not`. Why it matters: comparisons turn raw data into decisions.
- [ ] **Assignment operators** — `+=`, `-=`, `*=`, `/=`. Why it matters: they are the compact form you will read everywhere.
- **Deliverable:** a script `bill.py` that splits a bill between people, rounds to 2 decimals, and prints the share.
- **Worksheet:** [Day 5](worksheet/day-5.md)

## Day 6 — Saturday 17 Oct 2026 — If / elif / else

**Watch:** [1:39:27 – 2:16:14](https://youtu.be/_aWbUudZ5Yo?t=5967)

- [ ] **`if` statements** — `1:39:27` · running code only when a condition holds. Why it matters: branching is what turns a recipe into a program.
- [ ] **`if` / `else` and `elif` chains** — handling more than two outcomes. Why it matters: real rules always have more than one case.
- [ ] **Nested conditions & truthiness** — conditions inside conditions, and how Python treats empty values as false. Why it matters: avoids bugs like `if x == True`.
- **Deliverable:** a script `grade.py` that takes a score and prints the matching letter grade, with a message for invalid input.
- **Worksheet:** [Day 6](worksheet/day-6.md)

## Day 7 — Sunday 18 Oct 2026 — Practice: combine everything up to if-else

**Watch / re-watch:** any part of [0:00 – 2:16:14](https://youtu.be/_aWbUudZ5Yo?t=0) you found hard.

- [ ] **Re-run every deliverable** from Day 1 to Day 6 and confirm each one runs cleanly.
- [ ] **Debug a broken script** — take a program with a `NameError` and a `TypeError` and fix both. Why it matters: reading tracebacks is a daily skill.
- [ ] **Mini project** — a single script that asks for a few inputs and uses variables, types, operators, and `if` / `elif` / `else` to produce a result (for example a movie-ticket price calculator by age). Why it matters: combining the week's ideas is the real test.
- **Deliverable:** `miniproject.py` with input, a decision, and a formatted output.
- **Worksheet:** [Day 7](worksheet/day-7.md)

## Monday 19 Oct 2026 — Review, catch-up, and worksheet completion

- [ ] **Review the week** — read back every day's deliverable and confirm each one runs.
- [ ] **Catch up on anything missed**, using the official Python tutorial as your reference.
- [ ] **Complete every day worksheet** you have not finished yet.
- [ ] **Fill the week reflection** at the end of the checklist.

---

## Documentation (read after all 7 days)

Work through these once you have finished the days above — they are the official references you will
keep coming back to.

- **The Python Tutorial — An Informal Introduction:** https://docs.python.org/3/tutorial/introduction.html
- **Built-in Types (int, float, str, bool, list, dict):** https://docs.python.org/3/library/stdtypes.html
- **Built-in Functions (`input`, `print`, `int`, `len`, `range`):** https://docs.python.org/3/library/functions.html
- **More Control Flow Tools (`if`, `for`, `while`):** https://docs.python.org/3/tutorial/controlflow.html
- **Data Structures (lists, tuples, sets, dicts):** https://docs.python.org/3/tutorial/datastructures.html
- **Errors and Exceptions:** https://docs.python.org/3/tutorial/errors.html
- **Real Python — operators and expressions:** https://realpython.com/python-operators-expressions/
- **Real Python — strings:** https://realpython.com/python-strings/

## Week reflection

- **Biggest takeaway this week:** _______________________________________________
- **Blocker or stumbling point:** _______________________________________________
- **Open question:** _______________________________________________
- **One topic I want to revisit:** _______________________________________________
- **Goal for next week:** _______________________________________________
