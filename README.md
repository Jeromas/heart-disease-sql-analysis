# 🫀 heart-disease-sql-analysis

A data-driven exploration of cardiovascular risk using SQL queries and embedded SQLite in Google Colab.

---

## 📌 Project Overview

This notebook demonstrates how to perform SQL-based exploratory data analysis on a clinical heart disease dataset using SQLite in a Python environment (Google Colab).  
It uses the UCI Heart Disease (Cleveland) dataset to reveal patient-level patterns in age, cholesterol, gender, chest pain types, and more.

---

## ⚙️ Environment
- Google Colab (Python)
- SQLite via `sqlite3`
- Libraries: `pandas`, `matplotlib`, `seaborn`

---

## 💡 Key Skills Demonstrated
- SQL querying with Python
- SQLite database creation in-memory
- Google Colab + pandas integration
- Data wrangling, summary stats, and exploratory charts
- Dashboard-style tabular summaries

---

## 📁 Dataset
- Source: [UCI Heart Disease Dataset](https://archive.ics.uci.edu/dataset/45/heart+disease)
- Focused subset: Cleveland dataset (processed)
- Format: `.data` file (converted to dataframe and SQL table)

---

## 📊 Key Findings

- **45.9%** of patients show signs of heart disease (num > 0)
- **Asymptomatic chest pain** was the most reported type (47.5%)
- **Males** had a higher heart disease prevalence (55.3%) than females (25.7%)
- Average patient age: **54.4 years**

---

## 📋 Dashboard Summary (Non-Visual)

| Section                    | Key Insight |
|---------------------------|-------------|
| Total Patients            | 303         |
| Heart Disease Prevalence  | 139 patients (45.87%) |
| Average Age               | 54.4 years  |
| Gender Distribution       | 206 males, 97 females |
| Chest Pain Types          | 4 types (most common: Asymptomatic) |

---

##  Next Steps

- Apply Logistic Regression or Decision Trees for heart disease prediction
- Deploy insights into a Streamlit or Tableau dashboard
- Extend to other medical datasets

---

## 🔗 Author & Links

**Alphonso J. Saiewane**  
📌 [GitHub Portfolio](https://github.com/Jeromas)  
📰 [Substack Article (Coming Soon)](https://your-substack-link-here)

---

## 🪪 License
This project is licensed under the [MIT License](LICENSE).
