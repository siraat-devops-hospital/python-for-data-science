# 🧠 **1. Purpose of the Lab**

> This lab teaches you how to **use Jupyter Notebook like a pro** — combining code, documentation, and data in one place.

You’ll learn to:

* Write code in **Code Cells**
* Create clean documentation in **Markdown Cells**
* Load and explore real datasets using **Pandas**
* Get comfortable with Jupyter’s basic layout and workflow

---

## 🖥️ **2. Dataset Used**

**`employee_insights.csv`**
It contains:

* 👩‍💼 Employee demographics (age, gender, role)
* 🏢 Department data
* 📈 Performance metrics
* ⏳ Experience details

💡 *This is a realistic corporate dataset for your practice — similar to what analysts work on in HR or operations analytics.*

---

## 🔹 **3. Activity 1: Notebook Setup & Markdown**

### **Step 1: Create a Title**

Make your notebook readable and professional:

```markdown
# Employee Insights Analysis
## Exploring workforce performance with Python
```

✅ *Use “Markdown” cell type from dropdown.*
✅ *Run it with Shift + Enter to format it.*

---

### **Step 2: Markdown Formatting Practice**

Try this inside a new Markdown cell:

```markdown
**Bold text**
*Italic text*
- Bullet point one
- Bullet point two
```

✅ Helps you **document and explain** your analysis clearly.
✅ Great for client reports or portfolio notebooks.

> 💡 *In professional projects, Markdown is your storytelling layer — it turns code into a presentation.*

---

## 🔸 **4. Activity 2: Basic Python Operations**

### **Step 1: Create and Print Variables**

```python
company_name = "TechCorp"
employee_count = 100

print(f"Welcome to {company_name}!")
print(f"Total Employees: {employee_count}")
```

✅ Learn to store and display info dynamically using `f""` strings.

### **Step 2: Try It Yourself**

Make your own variables:

```python
department_name = "Data Science"
average_salary = 85000
current_year = 2025

print(f"Department: {department_name}")
print(f"Average Salary: ${average_salary}")
print(f"Year: {current_year}")
```

> ⚙️ *These basics (variables + print) are the foundation for all your data analysis scripts.*

---

## 📊 **5. Activity 3: Working with Data**

### **Step 1: Import Libraries & Load Dataset**

```python
import pandas as pd

df = pd.read_csv('employee_insights.csv')
```

✅ `pandas` = your **data wrangling** toolkit
✅ `read_csv()` loads Excel-style data into a DataFrame

---

### **Step 2: Explore the Data**

```python
display(df.head())    # First 5 rows
df.info()             # Column names, data types, and null values
```

✅ `head()` gives you a preview
✅ `info()` gives structure insight
✅ You’ll use both before any analysis to understand your data.

> 💡 *Always inspect data first — never analyze blind.*

---

## ✅ **6. Test Your Work**

After running all cells:

* ✔️ Markdown displays formatted text
* ✔️ Python cells print outputs
* ✔️ Dataset loads successfully
* ✔️ No errors in console

---

## 🧩 **7. Success Checklist**

| Task                       | Completed |
| -------------------------- | --------- |
| Markdown cells formatted   | ✅         |
| Python code executed       | ✅         |
| Dataset loaded             | ✅         |
| All print outputs verified | ✅         |

---

## 🛠️ **8. Common Errors & Fixes**

| Problem                 | Reason                                    | Solution                                  |
| ----------------------- | ----------------------------------------- | ----------------------------------------- |
| Markdown not formatting | Cell type is “Code” instead of “Markdown” | Change dropdown to “Markdown”             |
| Dataset not loading     | File path incorrect                       | Ensure file is in same folder as notebook |
| Code not running        | Missed Shift+Enter                        | Select cell → press **Shift+Enter**       |

---

## 🧾 **9. Summary**

You have now:

* Navigated the **Jupyter interface**
* Practiced Markdown formatting
* Run Python code cells
* Loaded and explored a dataset

💡 These steps form the **core workflow of every data scientist** — write, document, analyze, repeat.

---

## 🔑 **Key Points**

* Jupyter combines **code + text** for clean, interactive reports
* Markdown = your documentation tool
* Code cells = your execution environment
* Pandas = your data analysis engine
* Practice saves time later when you work with larger datasets

---
