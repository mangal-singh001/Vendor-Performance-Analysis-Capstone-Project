Got it 👍 Let’s create a **README.md** file for your repo: **Vendor-Performance-Analysis-Capstone-Project**.
Based on what you told me earlier (6 raw data files → ingestion → final dataset → EDA → dashboard), here’s a professional README draft you can directly add to your repo.

---

# 📊 Vendor Performance Analysis – Capstone Project

## 📌 Project Overview

This project focuses on analyzing vendor performance using real-world purchase and supplier data.
The goal is to evaluate suppliers based on delivery, quality, and cost efficiency to help businesses make data-driven decisions when managing vendors.

The workflow includes:

1. **Data Ingestion** – Multiple raw files are uploaded and stored in a local SQLite database.
2. **Data Processing** – Data is cleaned, merged, and transformed into a final dataset for analysis.
3. **Exploratory Data Analysis (EDA)** – Trends, distributions, and relationships are explored.
4. **Dashboard Creation** – An interactive **Power BI Dashboard** is built for insights.

---

## 🗂️ Dataset

* **Source**: 6 different CSV files (purchases, suppliers, etc.)
* **Storage**: SQLite local database
* **Final Dataset**: A single consolidated file used for EDA and dashboard

---

## ⚙️ Tech Stack

* **Python** 🐍

  * pandas, numpy – data cleaning & transformation
  * sqlite3 – database connection
  * matplotlib, seaborn – EDA visualization
* **SQL** 🗄️

  * Database setup & queries
* **Power BI** 📊

  * Interactive dashboard for business insights

---

## 🚀 Project Workflow

### 1. Data Ingestion

* Python script (`ingestion_db.py`) loads all raw files into SQLite database.

### 2. Data Cleaning & Processing

* Handled missing values, duplicates, and formatting.
* Joined datasets into one **final consolidated dataset**.

### 3. Exploratory Data Analysis

* Vendor performance distribution
* Top vendors by purchase value
* Late vs on-time delivery analysis
* Cost & quality trends

### 4. Power BI Dashboard

* KPIs: On-time delivery %, Quality rating, Purchase trends
* Visuals: Trend charts, bar plots, slicers, vendor comparison

---

## 📸 Dashboard Preview

![Dashboard Preview](Images/dashboard.png)
*(Replace with actual screenshot from your Power BI dashboard)*

---

## 📂 Repository Structure

```
Vendor-Performance-Analysis-Capstone-Project/
│-- data/                  # Raw data files  
│-- ingestion_db.py        # Script to ingest data into SQLite  
│-- data_processing.py     # Script to clean & merge data  
│-- eda.ipynb              # Exploratory Data Analysis  
│-- dashboard.pbix         # Power BI dashboard file  
│-- README.md              # Project documentation  
```

---

## 📈 Key Insights

* Identified top-performing vendors in terms of **quality and timely delivery**.
* Found patterns in **cost inefficiencies** across certain suppliers.
* Built an interactive dashboard for **quick business decisions**.

---

## 👨‍💻 Author

**Mangal Singh**

* [GitHub](https://github.com/mangal-singh001)
* [LinkedIn](https://www.linkedin.com/in/mangal-singh123/)

---

✨ *This project helped me strengthen my skills in Python, SQL, and Power BI while solving a real-world business problem.*

---

Would you like me to **add some emojis in section headers** (like we did in your other projects) to make it look more engaging, or keep it **professional and clean**?
