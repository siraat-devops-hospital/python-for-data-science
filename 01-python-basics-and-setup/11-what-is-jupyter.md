# 🧠 **1. What Is Jupyter Notebook?**

> Jupyter Notebook = Your **data science lab** 🧪
> A place where you can:

* Write code
* Document your logic
* Run code **block by block**
* See results **instantly**

🎯 **Use it to:**
Clean data, visualize trends, run ML models, and explain your process — *all in one file* (`.ipynb`).

---

## 🖥️ **2. The Workspace**

Each Jupyter Notebook contains **cells**:

* **Code Cells** → Run Python code
* **Markdown Cells** → Write notes, headings, lists, etc.

👉 To add a new cell → click ➕
👉 To change type → select from dropdown (“Code” or “Markdown”)
👉 To run a cell → **Shift + Enter**

---

## ✍️ **3. Markdown — Documentation Power**

Markdown helps you keep your notebook *clean and readable*.

| Action      | Syntax         | Example                      |
| ----------- | -------------- | ---------------------------- |
| Heading 1   | `#`            | `# Project Overview`         |
| Heading 2   | `##`           | `## Data Summary`            |
| Bullet List | `-`            | `- Sales Data`               |
| Bold        | `**text**`     | **bold**                     |
| Italic      | `*text*`       | *italic*                     |
| Link        | `[title](URL)` | [Google](https://google.com) |

💡 *Good documentation = professional-looking notebook + easy understanding for recruiters or teammates.*

---

## 🧩 **4. Writing Python Code in Jupyter**

### 🔸 Variables

```python
company_name = "TechCore"
employeeCount = 100
print(f"{company_name} has {employeeCount} employees.")
```

✅ `f""` before quotes → allows inserting variables with `{}`
✅ Output displays instantly below the cell

---

### 🔸 Lists & Loops

```python
departments = ["Sales", "Marketing", "IT"]

for department in departments:
    print(f"Department: {department}")
```

✅ Jupyter shows each line output neatly
✅ Use this for iterating datasets or testing filters

---

## 📊 **5. Working with Real Data**

This is where data science actually begins 🔥

```python
import pandas as pd

df = pd.read_csv("data.csv")
print(df.head())
```

✅ `import pandas` → loads data-handling library
✅ `.read_csv()` → imports CSV dataset into a **DataFrame**
✅ `.head()` → shows first 5 rows (for quick check)

💡 *Jupyter automatically formats tables beautifully — perfect for exploration.*

---

## 💾 **6. Saving & Organizing Work**

* 💡 Save notebook → `Ctrl + S` or File → Save
* 🔁 Rename files clearly (e.g., `01_Data_Cleaning.ipynb`)
* 🗂️ Keep notebooks organized by project phase
  (e.g., `/data/`, `/analysis/`, `/visuals/`)

✅ Always save before closing to avoid losing unsaved code/output.

---

## ⚡ **7. Quick Navigation Tips**

| Action             | Shortcut        |
| ------------------ | --------------- |
| Run cell           | `Shift + Enter` |
| Add cell below     | `B`             |
| Add cell above     | `A`             |
| Delete cell        | `D D`           |
| Change to Markdown | `M`             |
| Change to Code     | `Y`             |
| Interrupt run      | `Esc + I I`     |

---

## 🎯 **8. Key Takeaways**

* You can now **write, run, and document** Python in one place
* Use **Markdown** for clarity
* Use **Code cells** for logic
* Practice loading and exploring CSV data with **Pandas**
* Save and name your work professionally

> 💬 *Jupyter Notebook isn’t just a coding tool — it’s your portfolio builder.*
> Every notebook you create can later become a **GitHub project** or **freelance sample**.

---
