# Track B — Day 3 Worksheet — OOP: inheritance & polymorphism

**Name:** Kavya Srivastava  **GitHub handle:** https://github.com/kavyasrivastava769-bot
**Track:** Track B (Advanced Python)  **Day:** 3  **Date:** Wednesday 14 Oct 2026

> Fill in the gaps. Run every program and paste the **real** output.

---

## Question 1 — Inheritance

Write a base class `Shape` with a method `area()` that returns `0`, and subclasses `Circle(radius)` and
`Rectangle(width, height)` that override `area()`. Use `super().__init__()` where useful.

**Your code:**

```python
# write your program here
import math

class Shape:
    def __init__(self):
        pass

    def area(self):
        return 0


class Circle(Shape):
    def __init__(self, radius):
        super().__init__()
        self.radius = radius

    def area(self):
        return math.pi * self.radius ** 2


class Rectangle(Shape):
    def __init__(self, width, height):
        super().__init__()
        self.width = width
        self.height = height

    def area(self):
        return self.width * self.height



s = Shape()
c = Circle(5)
r = Rectangle(4, 6)

print("Shape area:", s.area())
print("Circle area:", round(c.area(), 2))
print("Rectangle area:", r.area())


```

**Output (circle r=3, rectangle 4x5):**

```
Shape area: 0
Circle area: 78.54
Rectangle area: 24
```
---

## Question 2 — Polymorphism

Create a list holding one `Circle` and one `Rectangle` and loop over it printing each `area()`. Explain
in one line what makes this work.

**Your code:**

```python
# write your program here
class Shape:
    def area(self):
        return 0

class Circle(Shape):
    def __init__(self, radius):
        self.radius = radius

    def area(self):
        return 3.14 * self.radius * self.radius

class Rectangle(Shape):
    def __init__(self, width, height):
        self.width = width
        self.height = height

    def area(self):
        return self.width * self.height

shapes = [Circle(5), Rectangle(4, 6)]

for shape in shapes:
    print(shape.area())

    #One-line explanation: Polymorphism allows the same area() method to behave differently for Circle and Rectangle objects.'''


```

**Why does the loop not need to know which class each object is?**
The loop does not need to know the class because polymorphism allows each object to call its own area() method automatically.

---

## Question 3 — Case study: a safe bank account

Write a `BankAccount` class where the balance is **private** (name it `_balance`). Provide `deposit()`
and `withdraw()` methods; `withdraw()` must refuse amounts larger than the balance.

**Your code:**

```python
# write your program here
class BankAccount:
    def __init__(self, balance):
        self._balance = balance

    def deposit(self, amount):
        self._balance += amount

    def withdraw(self, amount):
        if amount <= self._balance:
            self._balance -= amount
        else:
            print("Insufficient balance")

account = BankAccount(1000)

account.deposit(500)
account.withdraw(300)
print(account._balance)


```

**Output (deposit 1000, withdraw 300, withdraw 5000):**

```
1200
```

**Why is it safer to force callers to use `withdraw()` instead of editing `_balance` directly?**
Encapsulation protects the balance from direct changes and ensures that withdraw() checks the amount before updating it, maintaining data integrity.
