# 🧠 **Python Basics Cheat Sheet — Data Science Edition**

---

## ⚙️ **1. Syntax & Structure**

```python
# Comment
if condition:
    statement
else:
    statement
```

✅ Python uses **indentation (4 spaces)**, not `{}`
✅ Case-sensitive → `Name` ≠ `name`

---

## 🔢 **2. Core Data Types**

| Type      | Example         | Notes              |
| --------- | --------------- | ------------------ |
| **int**   | `x = 10`        | Whole number       |
| **float** | `pi = 3.14`     | Decimal            |
| **str**   | `"Hello"`       | Text (use quotes)  |
| **bool**  | `True`, `False` | Logical values     |
| **None**  | `None`          | Null / empty value |

---

## 📦 **3. Variables**

```python
x = 5
name = "Alice"
price = 19.99
```

✅ Dynamically typed
✅ Use clear, lowercase names: `total_sales`, `avg_temp`

---

## 📋 **4. Data Structures**

### 🧺 **List** — ordered, changeable

```python
fruits = ["apple", "banana", "cherry"]
print(fruits[0])         # apple
fruits.append("grape")   # add
```

### 🗝️ **Dictionary** — key/value pairs

```python
person = {"name": "Alice", "age": 25}
print(person["name"])    # Alice
person["age"] = 26       # update
```

### 🧩 **Set** — unique, unordered

```python
nums = {1, 2, 3, 3}
print(nums)              # {1, 2, 3}
```

### 🔒 **Tuple** — ordered, immutable

```python
coords = (10, 20)
print(coords[0])         # 10
```

---

## 🔁 **5. Control Flow**

### ➤ **If / Else**

```python
if age >= 18:
    print("Adult")
else:
    print("Minor")
```

### ➤ **For Loop**

```python
for fruit in fruits:
    print(fruit)
```

### ➤ **While Loop**

```python
count = 0
while count < 3:
    print(count)
    count += 1
```

---

## 🧩 **6. Functions**

```python
def greet(name):
    return f"Hello, {name}!"
```

✅ Call: `greet("Alice")`
✅ Use `return` to send output back
✅ `f""` strings embed variables cleanly

---

## 🧮 **7. Useful Built-ins**

| Function                | Purpose                     |
| ----------------------- | --------------------------- |
| `len(x)`                | length                      |
| `type(x)`               | check data type             |
| `int(), float(), str()` | convert types               |
| `sum(), min(), max()`   | basic math                  |
| `sorted(list)`          | returns new sorted list     |
| `range(n)`              | generate sequence for loops |

---

## 📊 **8. Working With Data**

### 🧹 List Comprehension

```python
squares = [x**2 for x in range(5)]
```

### 🔍 Conditional Inline

```python
status = "Adult" if age >= 18 else "Minor"
```

---

## 🧰 **9. Common Libraries (for Data Science)**

| Library                  | Purpose                      |
| ------------------------ | ---------------------------- |
| **Pandas**               | Data manipulation & analysis |
| **NumPy**                | Numerical computing          |
| **Matplotlib / Seaborn** | Visualization                |
| **Scikit-learn**         | Machine learning             |
| **Jupyter**              | Interactive notebook         |

---

## 💾 **10. File & Data Handling**

```python
# Read text file
with open("data.txt", "r") as f:
    content = f.read()

# Pandas CSV example
import pandas as pd
df = pd.read_csv("data.csv")
```

---

## 🧩 **11. GitHub Version Control (Quick)**

```bash
git init
git add .
git commit -m "First commit"
git push origin main
```

✅ Always commit changes with clear messages
✅ Keep your project + notebook organized

---

## 🧠 **12. Pro Tips**

* Practice daily → 20-30 min coding habit
* Use **Jupyter Notebook** for testing & documenting
* Comment your code clearly
* Save sample datasets for practice (`.csv`, `.json`)
* Build a **GitHub portfolio** with your notebooks

---

### ⚡ **Shortcut Recap**

| Action              | Shortcut            |
| ------------------- | ------------------- |
| Run cell (Jupyter)  | `Shift + Enter`     |
| Comment / Uncomment | `Ctrl + /`          |
| Copy last command   | `↑` (arrow up)      |
| Interrupt kernel    | `Esc + I I`         |
| Restart kernel      | `0 0` (press twice) |

---

### 🎯 **Next Steps**

Once you’re solid with this sheet:

1. Move to **Pandas** for data analysis
2. Practice **visualizations (Matplotlib / Seaborn)**
3. Start a small project (CSV → analysis → dashboard)
4. Upload to **GitHub portfolio**

---
