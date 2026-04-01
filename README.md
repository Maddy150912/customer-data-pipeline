# Customer Data Processing & Analytics Pipeline

## 📌 Overview
This project demonstrates an end-to-end data processing and analytics pipeline using Python and SQL. The objective is to clean, transform, and analyze customer shopping behavior data to generate meaningful business insights.

---

## ⚙️ Tech Stack
- Python (Pandas)
- SQL Server
- SQL (CTEs, Window Functions, Aggregations)
- SQLAlchemy

---

## 🔄 Workflow

### 1. Data Processing (Python)
- Loaded raw dataset using Pandas
- Handled missing values using median-based imputation
- Cleaned and standardized column names
- Performed feature engineering:
  - Age group segmentation
  - Purchase frequency mapping
- Validated data for consistency

### 2. Data Storage
- Connected Python to SQL Server using SQLAlchemy
- Loaded processed dataset into a structured database table

### 3. Data Analysis (SQL)
Performed business analysis using SQL:
- Revenue analysis by gender
- Product performance ranking
- Customer segmentation (New, Returning, Loyal)
- Discount impact analysis
- Subscription behavior insights

---

## 📊 SQL Output
SQL query results and outputs are documented in the file:

📄 **[SQL Output Document](docs/sql_output_document.pdf)**

This document contains screenshots of query outputs for all business questions.

---

## 📁 Project Structure
```
customer-data-pipeline/
│── data/
│ └── customer_shopping_behavior.csv
│
│── notebooks/
│ └── data_cleaning.ipynb
│
│── sql/
│ └── data_analysis.sql
│
│── output/
│ └── cleaned_data.csv
│
│── docs/
│ └── sql_output_document.pdf
│
│── README.md
```
---

## 🚀 Key Insights
- Identified top-performing products based on customer ratings
- Analyzed customer segments and purchasing behavior
- Compared revenue contribution across demographics
- Evaluated impact of discounts and subscriptions

---

## 🎯 Outcome
Built a complete data pipeline from raw data to actionable insights, demonstrating skills in data processing, data engineering, and analytics.

---

## 🔮 Future Improvements
- Automate pipeline using scheduling tools
- Scale processing using PySpark
- Deploy as a production-ready workflow

---
## 👨‍💻 About Me

Hi, I'm Mandar Yangal — a data professional with 2 years of experience in data operations, validation, and backend processes. I have hands-on experience in SQL, Power BI, and Python, and have built end-to-end data projects involving data cleaning, transformation, modeling, and visualization.

Currently, I am expanding my skill set by learning Apache Spark (PySpark) on Databricks, focusing on big data processing and data engineering workflows. I am actively seeking opportunities in Data Analytics or Data Engineering roles where I can contribute to data-driven decision-making and continue growing in the data domain.

🔗 **Connect with me:**  

[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-blue?style=for-the-badge)](https://my-portfolio-eight-lime-40.vercel.app/) [![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/in/mandar-yangal-a72098262) [![Instagram](https://img.shields.io/badge/Instagram-Follow-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://www.instagram.com/mr.maddy150912/) [![Gmail](https://img.shields.io/badge/Gmail-Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:mandar.yangal15@gmail.com)

---

⭐ If you found this project useful, feel free to star the repository!
