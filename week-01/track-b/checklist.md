# Track B — Advanced Python: Week 1 Checklist

**Track B** is for members who are comfortable with variables, functions, and loops and want to move
toward Python libraries. Work through the checklist in order, one day at a time. Every day ends with a
hands-on deliverable — watching alone is not the work. Flip each `- [ ]` to `- [x]` as you finish, then
commit your changes in your own fork.

**Source video:** [Python Full Course for Beginners to Advanced (12 hours)](https://youtu.be/_aWbUudZ5Yo)
**Week:** Mon 12 Oct 2026 → Mon 19 Oct 2026 · **7 topic days** (Mon–Sun) + a review Monday.
**Goal by Monday 19 Oct:** exception handling, file handling, **OOP**, and the **advanced-Python
concepts**, ending with the Bank Management System project.
**Scope this week:** watch the course from **Exception handling to the end (6:23:24 → 11:34:50)**.

> Each day's questions live in the matching file under [`worksheet/`](worksheet/README.md), e.g. Day 1
> questions are in [`worksheet/day-1.md`](worksheet/day-1.md).

---

## Day 1 — Monday 12 Oct 2026 — Exception handling + file handling

**Watch:** [6:23:24 – 6:52:30](https://youtu.be/_aWbUudZ5Yo?t=23004)

- [ ] **Exception handling** — `6:23:24` · `try`, `except`, `else`, `finally`, and raising specific errors. Why it matters: bad input and missing files are guaranteed, not hypothetical.
- [ ] **Reading and writing files** — `6:43:23` · `open()`, modes, and `with` for clean-up. Why it matters: file I/O is the first step from pure computation to real data.
- **Deliverable:** `reader.py` that reads a text file inside a `try` block and prints a clear message if the file is missing.
- **Worksheet:** [Day 1](worksheet/day-1.md)

## Day 2 — Tuesday 13 Oct 2026 — File-handling project + OOP intro

**Watch:** [6:52:30 – 8:00:00](https://youtu.be/_aWbUudZ5Yo?t=24750)

- [ ] **File handling project** — `6:52:30` · build the file-based example from the video. Why it matters: it turns separate file operations into one working program.
- [ ] **Classes and objects** — `7:24:17` · `class`, `__init__`, attributes, and `self`. Why it matters: classes bundle data and behaviour into reusable tools.
- [ ] **Methods and `self`** — calling methods on objects. Why it matters: the biggest source of early confusion in Python.
- **Deliverable:** `student.py` with a `Student` class (name, marks) and a method that prints a summary.
- **Worksheet:** [Day 2](worksheet/day-2.md)

## Day 3 — Wednesday 14 Oct 2026 — OOP: inheritance & polymorphism

**Watch:** [8:00:00 – 9:18:32](https://youtu.be/_aWbUudZ5Yo?t=26657)

- [ ] **Inheritance and `super()`** — subclassing, overriding, and calling the parent class. Why it matters: lets you extend existing tools without rewriting them.
- [ ] **Polymorphism** — the same method name behaving differently per class. Why it matters: the core idea behind reusable, swappable components.
- [ ] **Encapsulation** — keeping data private and exposing methods. Why it matters: protects your data from accidental edits.
- **Deliverable:** `shapes.py` with a base `Shape` and subclasses `Circle` and `Rectangle`, each with its own `area()`.
- **Worksheet:** [Day 3](worksheet/day-3.md)

## Day 4 — Thursday 15 Oct 2026 — Advanced Python: comprehensions & lambdas

**Watch:** [9:18:32 – 9:45:00](https://youtu.be/_aWbUudZ5Yo?t=33512)

- [ ] **List comprehensions** — `9:18:32` · the compact form of mapping and filtering. Why it matters: the single most common Python idiom you will read and write.
- [ ] **Dict and set comprehensions** — building dictionaries and sets inline. Why it matters: the same idea applied to mappings and uniqueness.
- [ ] **Lambdas with `map` / `filter`** — small anonymous functions. Why it matters: they appear everywhere in libraries and notebooks.
- **Deliverable:** a script `comprehensions.py` that builds a list of squares, filters the even ones, and a dict of name → length, all in comprehension form.
- **Worksheet:** [Day 4](worksheet/day-4.md)

## Day 5 — Friday 16 Oct 2026 — Advanced Python: iterators, generators, decorators

**Watch:** [9:45:00 – 10:05:09](https://youtu.be/_aWbUudZ5Yo?t=33512)

- [ ] **Iterables and iterators** — the `iter()` / `next()` protocol. Why it matters: the foundation of `for` loops and of lazy data processing.
- [ ] **Generators with `yield`** — producing values one at a time. Why it matters: lets you process large data without loading it all into memory.
- [ ] **Decorators and modules** — wrapping functions and splitting code into files with `import`. Why it matters: how real Python projects are organised.
- **Deliverable:** `stream.py` with a generator that yields numbers from a file one line at a time, plus a small decorator that prints how long a function takes.
- **Worksheet:** [Day 5](worksheet/day-5.md)

## Day 6 — Saturday 17 Oct 2026 — OOP project: Bank Management System

**Watch:** [10:05:09 – 11:34:50](https://youtu.be/_aWbUudZ5Yo?t=36309)

- [ ] **Follow the Bank Management System project** — `10:05:09` · classes, methods, and a menu loop. Why it matters: your first complete object-oriented program.
- [ ] **Design your classes before coding** — list the classes and their methods on paper first. Why it matters: design before code is the habit that keeps projects from collapsing.
- [ ] **Add your own feature** — deposit/withdraw validation, or a transaction history list. Why it matters: extending the example is how you prove you understood it.
- **Deliverable:** `bank.py` that runs a menu with create-account, deposit, withdraw, and view-balance.
- **Worksheet:** [Day 6](worksheet/day-6.md)

## Day 7 — Sunday 18 Oct 2026 — Practice: consolidate advanced Python

**Watch / re-watch:** any part of [6:23:24 – 11:34:50](https://youtu.be/_aWbUudZ5Yo?t=23004) you found hard.

- [ ] **Re-run every deliverable** from Day 1 to Day 6 and confirm each one runs cleanly.
- [ ] **Pick the hardest idea this week** (a generator, a decorator, inheritance) and implement it from memory, then verify with a tiny script.
- [ ] **Refactor `bank.py`** into two files — a `models.py` for the classes and a `main.py` entry point — and run it. Why it matters: moves you from script to package.
- **Deliverable:** the refactored project tree and a successful run.
- **Worksheet:** [Day 7](worksheet/day-7.md)

## Monday 19 Oct 2026 — Review, catch-up, and worksheet completion

- [ ] **Review the week** — read back every day's deliverable and confirm each one runs.
- [ ] **Catch up on anything missed**, using the official Python docs as your reference.
- [ ] **Complete every day worksheet** you have not finished yet.
- [ ] **Fill the week reflection** at the end of the checklist.

---

## Documentation (read after all 7 days)

Work through these once you have finished the days above — they are the official references you will
keep coming back to.

- **Errors and Exceptions:** https://docs.python.org/3/tutorial/errors.html
- **Input and Output (files, formatting):** https://docs.python.org/3/tutorial/inputoutput.html
- **`csv` module:** https://docs.python.org/3/library/csv.html
- **Classes (OOP):** https://docs.python.org/3/tutorial/classes.html
- **Data Structures (comprehensions):** https://docs.python.org/3/tutorial/datastructures.html
- **Functional programming HOWTO (iterators, generators, `map`/`filter`):** https://docs.python.org/3/howto/functional.html
- **Modules:** https://docs.python.org/3/tutorial/modules.html
- **Virtual environments and packages (`venv`, `pip`):** https://docs.python.org/3/tutorial/venv.html
- **NumPy quickstart:** https://numpy.org/doc/stable/user/quickstart.html
- **pandas getting started:** https://pandas.pydata.org/docs/getting_started/index.html
- **Matplotlib pyplot tutorial:** https://matplotlib.org/stable/tutorials/pyplot.html

## Week reflection

- **Biggest takeaway this week:** _______________________________________________
- **Blocker or stumbling point:** _______________________________________________
- **Open question:** _______________________________________________
- **One topic I want to revisit:** _______________________________________________
- **Goal for next week:** _______________________________________________
