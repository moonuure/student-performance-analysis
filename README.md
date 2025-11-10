# 🎓 Student Performance Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-yellow?logo=pandas)
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-Machine_Learning-orange?logo=scikit-learn)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📘 Project Overview
This project explores and analyzes a **university student dataset** to identify the factors that most influence **academic performance (GPA)**.  
It combines **data cleaning**, **exploratory analysis**, and a **machine learning model (Random Forest)** to understand how variables such as study habits, scholarships, and parental education relate to academic outcomes.

---

## 🎯 Objectives
- Perform **data exploration and cleaning**.  
- Visualize patterns and relationships in student performance.  
- Build a **predictive model** for GPA using machine learning.  
- Evaluate model accuracy with **R²** and **RMSE** metrics.

---

## 🧰 Technologies Used
- **Python 3.x**
- **Pandas**, **NumPy**
- **Matplotlib**, **Seaborn**
- **Scikit-learn**

---

## 📊 Dataset

📦 **Source:** [Kaggle – Students Performance Dataset](https://www.kaggle.com/datasets/joebeachcapital/students-performance/data?select=StudentsPerformance_with_headers.csv)

The dataset contains detailed demographic, family, and academic information for each student.

| Category | Example Columns |
|-----------|----------------|
| **Demographics** | `Student Age`, `Sex`, `Scholarship type`, `Additional work` |
| **Family Background** | `Mother’s education`, `Father’s occupation`, `Parental status` |
| **Study Habits** | `Weekly study hours`, `Attendance to classes`, `Taking notes in classes` |
| **Performance** | `Cumulative GPA`, `Expected GPA at graduation`, `GRADE` |

---

## 🧮 Analysis Steps

### 1️⃣ Load and Inspect Data
```python
df.info()
df.describe()
df.head()
