# Hi there! 👋

I'm Ariful Hoque, a passionate Full Stack Developer on a journey to create digital magic. 🚀

## Coding Timeline 📅

- 🌱 Started coding at age 18.
- 💼 Joined BDtask in 2022.
- 🎓 Graduated from BRAC university in 2021.

## Tech Stack Evolution 🛠️

Here's how my tech stack has evolved over the years:

- 2020: Started with HTML, CSS, and JavaScript.
- 2019: Fell in love with Python.
- 2022: Explored machine learning and AI.
- 2022: Dabbled in full-stack development.
- 2023: Became obsessed with DevOps.

## Code Art Gallery 🎨

### The Fibonacci Sequence in Python

```python
def fibonacci(n):
    if n <= 0:
        return []
    elif n == 1:
        return [0]
    elif n == 2:
        return [0, 1]
    else:
        fib = [0, 1]
        while len(fib) < n:
            fib.append(fib[-1] + fib[-2])
        return fib
