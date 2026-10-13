# Track B — Day 2 Worksheet — File-handling project + OOP intro

**Name:** Kavya Srivastava **GitHub handle:** https://github.com/kavyasrivastava769-bot
**Track:** Track B (Advanced Python)  **Day:** 2  **Date:** Tuesday 13 Oct 2026

> Fill in the gaps. Run every program and paste the **real** output.

---

## Question 1 — Your first class

Write a `Student` class with `__init__` storing `name` and `marks`. Add a method `summary()` that
returns `"<name> scored <marks>"`. Create an object and print its summary.

**Your code:**

```python
# write your program here
class Student:
    def __init__(self, name, marks):
        self.name= name
        self.marks= marks
    def summary(self):
        return f"Name: {self.name}, Marks: {self.marks}"
student1= Student("kavya", 87)
print(student1.summary())



```

**Output:**

```
Name : Kavya, Marks: 87

```

**What does `self` refer to inside `summary()`?**

Here in `summary()` `self` refers to  the current object of the `Student` class on which method is called.

---

## Question 2 — File-handling project

Pick the file-based project from the video (or build a small one): read a text file of names, count how
many lines it has, and write the count into `count.txt`.

**Your code:**

```python




with open("input.txt", "r") as file:
    lines = file.readlines()

line_count = len(lines)

with open("count.txt", "w") as file:
    file.write(str(line_count))

print("Total lines:", line_count)
print("Line count saved to count.txt")


```
input.txt
Hi guys I am Kavya
I am doing my file handling project
hope it turns out good.

**Output / contents of `count.txt`:**


```
Output

3

in terminal
 Total lines: 3
 Line count saved to count.txt
```

---

## Question 3 — Case study: design a Library Book

Design a `Book` class for a small library. It should store a title, author, and a flag for whether the
book is issued. Add methods `issue()` and `return_book()` that flip the flag and return a status
message.

**Your code:**

```python

class Book:
    def __init__(self, title, author):
        self.title = title
        self.author = author
        self.is_issued = False

    def issue(self):
        if not self.is_issued:
            self.is_issued = True
            return "Book issued successfully."
        return "Book is already issued."

    def return_book(self):
        if self.is_issued:
            self.is_issued = False
            return "Book returned successfully."
        return "Book was not issued."

book1 = Book("The story behind glowing moon", "Kavy")

print(book1.issue())
print(book1.return_book())

Output

Book issued successfully.
Book returned successfully.
# write your program here


```

**Why should `issue()` and `return_book()` be methods on `Book` instead of plain functions?**
we shoud use  methods inside the Book class because issuing or returning a book changes that book’s own status. This also makes it easier to manage many books, since each book can keep track of whether it is issued or available.
