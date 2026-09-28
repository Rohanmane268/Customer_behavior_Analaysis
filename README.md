# Customer_behavior_Analaysis


# 📊 Data Analytics Project

## 📌 Overview

This project demonstrates an end-to-end **Data Analytics workflow**, starting from data loading and exploration in Python to SQL-based analysis, Power BI dashboard creation, report preparation, and presentation.

The main objective is to clean and analyze the dataset, identify meaningful patterns and insights, and present the findings through interactive visualizations and business-friendly reports.

---

## 📂 Dataset

The project uses a structured dataset containing relevant business/customer/sales information.

The dataset was:

* Loaded and explored using Python
* Checked for missing and duplicate values
* Cleaned and transformed for analysis
* Stored in a relational database for SQL analysis
* Connected to Power BI for dashboard development

**Dataset file:** `dataset.csv`

---

## 🛠️ Tools & Technologies

| Tool                                | Purpose                                 |
| ----------------------------------- | --------------------------------------- |
| **Python**                          | Data loading, cleaning, and EDA         |
| **Pandas**                          | Data manipulation and analysis          |
| **NumPy**                           | Numerical operations                    |
| **Matplotlib / Seaborn**            | Data visualization                      |
| **SQL**                             | Data querying and analysis              |
| **PostgreSQL / MySQL / SQL Server** | Database management                     |
| **Power BI**                        | Interactive dashboard and visualization |
| **DAX**                             | Measures and calculated analysis        |
| **Gamma**                           | Presentation/PPT creation               |
| **Excel/CSV**                       | Data storage and initial inspection     |

---

## 🔄 Project Steps

### 1. Load Dataset

The dataset was imported into Python using Pandas.

```python
import pandas as pd

df = pd.read_csv("dataset.csv")

print(df.head())
print(df.info())
```

---

### 2. Exploratory Data Analysis (EDA)

EDA was performed to understand the structure and characteristics of the data.

Key activities included:

* Understanding rows and columns
* Checking data types
* Identifying missing values
* Finding duplicate records
* Analyzing numerical columns
* Studying categorical variables
* Identifying trends and patterns
* Creating visualizations

---

### 3. Data Cleaning

The dataset was cleaned before performing detailed analysis.

Major cleaning activities included:

* Handling missing/null values
* Removing duplicate records
* Correcting data types
* Standardizing column names
* Handling inconsistent values
* Removing unnecessary columns
* Checking for outliers where required

The cleaned dataset was then prepared for SQL and Power BI analysis.

---

### 4. SQL Analysis

The cleaned data was imported into a relational database such as:

* PostgreSQL
* MySQL
* SQL Server

SQL queries were written to answer business-related questions and generate useful insights.

Examples of analysis:

```sql
-- Total records
SELECT COUNT(*) AS total_records
FROM sales;

-- Total revenue
SELECT SUM(revenue) AS total_revenue
FROM sales;

-- Revenue by category
SELECT category,
       SUM(revenue) AS total_revenue
FROM sales
GROUP BY category
ORDER BY total_revenue DESC;
```

SQL concepts used:

* `SELECT`
* `WHERE`
* `GROUP BY`
* `ORDER BY`
* `JOIN`
* `CASE`
* Aggregate functions
* Subqueries
* CTEs
* Window functions

---

## 📊 Power BI Dashboard

The analyzed data was connected to Power BI to create an interactive dashboard.

### Dashboard Features

* KPI cards
* Sales/Revenue analysis
* Category analysis
* Customer analysis
* Trend analysis
* Interactive slicers
* Charts and graphs
* Filters
* DAX measures

### Example KPIs

* Total Revenue
* Total Sales
* Total Customers
* Total Orders
* Average Order Value
* Profit
* Growth/Trend metrics

The dashboard allows users to interact with the data and quickly identify important business trends.

---

## 📈 Results & Insights

The analysis helped identify important patterns and trends within the dataset.

Key outcomes included:

* Identifying top-performing categories/products
* Understanding customer behavior
* Analyzing sales and revenue trends
* Finding areas with lower performance
* Comparing different business segments
* Supporting data-driven decision-making

The final insights were presented through the **Power BI dashboard, analytical report, and presentation**.

---

## 📝 Project Report

A detailed report was prepared covering:

1. Project Introduction
2. Business Problem
3. Dataset Description
4. Data Cleaning
5. Exploratory Data Analysis
6. SQL Analysis
7. Power BI Dashboard
8. Key Findings
9. Business Insights
10. Conclusion

---

## 🎤 Presentation

A professional presentation was created using **Gamma** to summarize the project.

The presentation includes:

* Project overview
* Business problem
* Data and methodology
* EDA findings
* SQL analysis
* Power BI dashboard
* Key insights
* Conclusion

---

## 🚀 How to Run

### Step 1: Clone the Repository

```bash
git clone https://github.com/yourusername/data-analytics-project.git
```

### Step 2: Open the Project

```bash
cd data-analytics-project
```

### Step 3: Install Python Libraries

```bash
pip install pandas numpy matplotlib seaborn
```

### Step 4: Run the Python Analysis

Open the Jupyter Notebook:

```text
data_analysis.ipynb
```

Run the notebook to perform data loading, cleaning, EDA, and visualization.

### Step 5: Run SQL Queries

Import the cleaned dataset into **PostgreSQL, MySQL, or SQL Server** and execute the SQL scripts available in:

```text
/sql/
```

# Step 6: Open Power BI Dashboard

Open:

```text
powerbi/dashboard.pbix
```

If required, update the database connection and refresh the data.

---

## 📁 Project Structure

```text
Data-Analytics-Project/
│
├── data/
│   └── dataset.csv
│
├── notebooks/
│   └── data_analysis.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── dashboard.pbix
│
├── report/
│   └── project_report.pdf
│
├── presentation/
│   └── project_presentation.pdf
│
└── README.md
```

---

## 🎯 Skills Demonstrated

* Python
* Pandas
* NumPy
* Exploratory Data Analysis
* Data Cleaning
* SQL
* PostgreSQL / MySQL / SQL Server
* Power BI
* DAX
* Data Visualization
* Business Analysis
* Data Storytelling
* Report Preparation
* Presentation Skills




