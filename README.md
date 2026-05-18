# Student Admission Analysis System

## 🎓 Project Overview

The **Student Admission Analysis System** is an end-to-end Data Analytics project designed to analyze student admission records using **SQL, Python, Power BI, and Tableau**.
This project helps identify admission trends, fee collection insights, student performance, course popularity, and admission confirmation patterns.

The dashboard provides interactive visualizations and business insights for better academic decision-making.

---

# 🚀 Tools & Technologies Used

| Tool                                                                      | Purpose                   |
| ------------------------------------------------------------------------- | ------------------------- |
| [Python](https://www.python.org?utm_source=chatgpt.com)                   | Data Cleaning & EDA       |
| [Pandas](https://pandas.pydata.org?utm_source=chatgpt.com)                | Data Manipulation         |
| [NumPy](https://numpy.org?utm_source=chatgpt.com)                         | Numerical Operations      |
| [Matplotlib](https://matplotlib.org?utm_source=chatgpt.com)               | Data Visualization        |
| [Seaborn](https://seaborn.pydata.org?utm_source=chatgpt.com)              | Statistical Charts        |
| [SQL Server](https://www.microsoft.com/sql-server?utm_source=chatgpt.com) | Data Querying             |
| [Power BI](https://powerbi.microsoft.com?utm_source=chatgpt.com)          | Dashboard Creation        |
| [Tableau](https://www.tableau.com?utm_source=chatgpt.com)                 | Interactive Visualization |
| [GitHub](https://github.com?utm_source=chatgpt.com)                       | Project Hosting           |

---

# 📂 Dataset Information

The dataset contains student admission records with details such as:

* Student ID
* Student Name
* Gender
* Course Applied
* Admission Status
* Entrance Exam Score
* Fees Paid
* Scholarship Status
* Admission Date
* City & State

---

# 📊 Project Workflow

```text
Data Collection
       ↓
Data Cleaning
       ↓
Exploratory Data Analysis (EDA)
       ↓
SQL Analysis
       ↓
Python Visualization
       ↓
Power BI Dashboard
       ↓
Tableau Dashboard
       ↓
Business Insights
```

---

# 🧹 Data Cleaning Process

Performed multiple cleaning steps including:

✔ Removed null values
✔ Removed duplicate records
✔ Corrected data types
✔ Standardized column names
✔ Fixed inconsistent values
✔ Converted date columns
✔ Handled missing fee values

---

# 🔍 Exploratory Data Analysis (EDA)

Analysis performed on:

* Admission confirmation rate
* Gender distribution
* Course-wise admissions
* Monthly admission trends
* Scholarship analysis
* Fee collection insights
* Entrance exam performance
* Student demographics

---

# 📈 SQL Analysis

### Sample SQL Queries

```sql
SELECT Course_Applied,
COUNT(*) AS Total_Students
FROM Admissions
GROUP BY Course_Applied
ORDER BY Total_Students DESC;
```

```sql
SELECT SUM(Fees_Paid) AS Total_Fees
FROM Admissions;
```

```sql
SELECT Admission_Status,
COUNT(*) AS Total
FROM Admissions
GROUP BY Admission_Status;
```

---

# 🐍 Python Visualizations

Created visualizations using Python libraries:

* Pie Charts
* Bar Charts
* Line Charts
* Histogram
* Heatmap
* Countplot

---

# 📊 Power BI Dashboard Features

## Dashboard KPIs

* Total Students
* Confirmed Admissions
* Total Fees Collected
* Average Entrance Score
* Scholarship Students %

## Dashboard Charts

* Admission Status Pie Chart
* Monthly Admission Trend
* Course-wise Analysis
* Gender Distribution
* Fees Analysis
* Top Courses

---

# 📌 Tableau Dashboard Features

* Interactive Filters
* Dynamic Charts
* Admission Trend Analysis
* Student Distribution Map
* Course Performance Dashboard
* Drill-down Insights

---

# 💡 Key Insights

* Computer Science course received the highest admissions.
* Majority of students successfully confirmed admissions.
* Fees collection showed positive monthly growth.
* Students with higher entrance scores had better admission chances.
* Scholarship students contributed significantly to admissions.

---

# 🏆 Project Highlights

✔ End-to-End Data Analytics Project

✔ Professional Dashboard Design

✔ Real-world Admission Dataset

✔ SQL + Python + Power BI + Tableau Integration

✔ Business Insight Generation

✔ Portfolio Ready Project

---


---

# ▶ How to Run the Project

## Clone Repository

```bash
git clone <repository-link>
```

## Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn openpyxl
```

## Run Python File

```bash
python analysis.py
```

---

# 📷 Dashboard Preview

<img width="1916" height="1021" alt="Screenshot 2026-05-18 153523" src="https://github.com/user-attachments/assets/417da969-f360-46d2-b4a0-11a593ee807f" />


# 📚 Future Improvements

* Machine Learning Admission Prediction
* Real-time Dashboard Integration
* Student Performance Forecasting
* Automated Reporting System

---

# 👨‍💻 Author

**Chaitnaya Darekar**


---

# ⭐ If You Like This Project

Give this repository a ⭐ on [GitHub](https://github.com/ChaitanyaDarekar) and support the project.
