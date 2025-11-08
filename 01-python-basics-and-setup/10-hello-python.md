# 🧠 **1. Python — Your Data Science Engine**

> Python is used everywhere — data science, AI, analytics, automation, etc.
> It’s simple, clean, and full of libraries (Pandas, NumPy, Matplotlib).

In this module, you’ll practice:

* Creating and using **variables**
* Storing data in **lists**
* Automating tasks with **loops**
* Writing reusable **functions**

---

## 🔹 **2. Variables — Data Storage Units**

A **variable** stores information (like text or numbers) so you can reuse it.

```python
company_name = "MediaCorp"
number_of_employees = 150
print(company_name)
print(number_of_employees)
```

🧩 **Key points:**

* Variables can hold many data types: `int`, `float`, `str`, `bool`, etc.
* Python is **dynamically typed** — no need to declare types.
* Always use **meaningful names**: `total_sales`, `user_name`, etc.

> 💡 *Good variable names make your code look professional and easy to debug.*

---

## 📋 **3. Lists — Store Multiple Values**

A **list** is a collection of items stored in one variable — perfect for datasets.

```python
employee_names = ["John", "Ana", "Lucy", "Bryan"]
print(employee_names)
```

🧩 **Key points:**

* Lists are **ordered and mutable** → you can modify them anytime.
* Access by index → `employee_names[0]` gives `"John"`.
* Lists are used heavily in **data cleaning & transformation**.

> 💡 *In data analysis, lists evolve into Pandas Series or DataFrame columns.*

---

## 🔁 **4. Loops — Automate Repetition**

### 🔸 **For Loop — Iterate Through a Sequence**

```python
for name in employee_names:
    print(name)
```

✅ Runs once for each item in the list
✅ Ideal for data iteration and reporting

### 🔸 **While Loop — Repeat Until Condition Ends**

```python
countdown = 5
while countdown > 0:
    print(countdown)
    countdown = countdown - 1
```

✅ Runs until condition is false
✅ Great for continuous checks or countdowns

> 💡 *Loops are your automation tools — perfect for batch cleaning, feature extraction, or processing data rows.*

---

## 🧩 **5. Functions — Reusable Mini Programs**

Functions help organize your code — define once, use anywhere.

### **Built-in Functions**

Python already gives you many:

```python
print("Welcome to MediaCorp!")     # Display text
print(len(employee_names))         # Count items in a list → 4
salaries = [55000, 62000, 48000, 75000]
print(sum(salaries))               # Add all → 240000
```

🧠 Common built-ins:
`type(), max(), min(), sorted(), range(), list(), dict(), sum(), len()`

---

### **Custom Function**

Make your own for flexibility:

```python
def greet_employee(name):
    print("Welcome to MediaCorp,", name)

greet_employee("John")

for name in employee_names:
    greet_employee(name)
```

🧩 **Concepts:**

* Use `def` to define a function
* Parameters → inputs inside `()`
* Use **loops inside functions** for repeated automation
* Keep names **action-oriented** (e.g., `calculate_salary`, `filter_data`)

> 💬 *Functions are how you modularize and reuse code in projects.*

---

## 🧾 **6. Summary — What You Learned**

| Concept        | Purpose               | Example                  |
| -------------- | --------------------- | ------------------------ |
| **Variable**   | Store single data     | `x = 10`                 |
| **List**       | Store multiple values | `names = ["John","Ana"]` |
| **For Loop**   | Repeat for sequence   | `for name in names:`     |
| **While Loop** | Repeat until false    | `while x > 0:`           |
| **Function**   | Reusable code block   | `def greet(name):`       |

---

## 🎯 **7. Why This Matters for Data Science**

✅ These are **the foundation for everything** in Python data workflows:

* Lists → evolve into Pandas Series
* Loops → handle row-by-row transformations
* Functions → automate cleaning, visualization, ML preprocessing
* Variables → structure all your data

> ⚡ *Once you master this, you can jump straight into Pandas, NumPy, and real data projects.*

---

## 🧠 **Pro Practice Tip**

Try combining all concepts:

```python
# Practice mini-project
salaries = [55000, 62000, 48000, 75000]
def average_salary(salaries):
    total = sum(salaries)
    avg = total / len(salaries)
    return avg

print(f"Average Salary: {average_salary(salaries)}")
```

💡 Output → `Average Salary: 60000.0`

---
