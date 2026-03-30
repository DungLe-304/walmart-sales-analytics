# 🛒 Walmart Sales Data Analysis

An end-to-end exploratory data analysis (EDA) project on Walmart transactional sales data from three branches across Yangon, Mandalay, and Naypyitaw (Jan–Mar 2019). This project includes SQL-based analysis and an interactive HTML dashboard built for portfolio purposes.

🔗 **[Live Dashboard →](https://DungLe-304.github.io/walmart-sales-analysis/walmart_dashboard.html)**

---

## 📌 Project Overview

This project analyzes 1,000 sales transactions across three branches — Yangon, Mandalay, and Naypyitaw — to uncover revenue trends, customer behavior patterns, and product line performance.

**Key questions answered:**
- Which branch and product line generate the most revenue?
- What time of day and day of week drive the most sales?
- How do customer types (Member vs. Normal) and gender affect purchasing behavior?
- Which payment method is most commonly used?
- What is the average customer satisfaction rating across categories?

---

## 📊 Interactive Dashboard

The dashboard (`walmart_dashboard.html`) is a fully self-contained, browser-ready file featuring:

- **5 KPI cards** — Total Revenue, Transactions, Avg Order Value, Avg Rating, Gross Income
- **7 interactive charts** — Monthly revenue by branch, product line revenue, day-of-week trends, payment distribution, time-of-day analysis, gender breakdown, and branch comparison
- **Filter controls** — Slice data by Branch, Product Line, Customer Type, Gender, and Payment Method
- **Sortable summary table** — Product line performance with Good/Bad performance badges

No server or dependencies required — just open the `.html` file in any browser.

---

## 🔍 Key Findings

| Insight | Finding |
|---|---|
| 💰 Top revenue branch | Naypyitaw (Branch C) — **$110,568** |
| 🏆 Best product line | Food and Beverages — **$56,145** |
| 🕐 Peak sales time | **Afternoon** (365 transactions, $122K revenue) |
| 📅 Busiest day | **Saturday** (164 transactions) |
| ⭐ Highest-rated category | Food and Beverages — **7.11 / 10** |
| 💳 Most used payment | Ewallet & Cash — nearly tied (~34% each) |
| 👥 Customer split | Members vs. Normal — almost equal (501 vs. 499) |
| 📈 Gross margin | Consistent **4.76%** across all product lines |

---

## 🗂️ Project Structure

```
walmart-sales-analysis/
│
├── WalmartSalesData.csv       # Raw dataset (1,000 rows)
├── SQL_queries.sql            # MySQL queries for EDA
├── walmart_dashboard.html     # Interactive analytics dashboard
└── README.md
```

---

## 🛠️ Tech Stack

| Tool | Usage |
|---|---|
| **MySQL** | Data cleaning, feature engineering, exploratory queries |
| **HTML / CSS / JavaScript** | Interactive dashboard (no frameworks) |
| **Chart.js** | Data visualization (7 chart types) |
| **Python** | Data aggregation for dashboard pre-computation |

---

## 🚀 How to Use

**View the dashboard locally:**
1. Clone this repository
2. Open `walmart_dashboard.html` in any web browser
3. Use the filter dropdowns to explore the data

**Run the SQL queries:**
1. Import `WalmartSalesData.csv` into MySQL
2. Run the schema setup at the top of `SQL_queries.sql`
3. Execute individual queries to reproduce the analysis

---

## 📁 Dataset

- **Source:** [Kaggle — Walmart Sales Forecasting](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting)
- **Period:** January 2019 – March 2019
- **Records:** 1,000 transactions
- **Branches:** Branch A (Yangon), Branch B (Mandalay), Branch C (Naypyitaw)
- **Features:** Invoice ID, Branch, City, Customer Type, Gender, Product Line, Unit Price, Quantity, Tax, Total, Date, Time, Payment Method, COGS, Gross Income, Rating

---

## 👤 Author

**Tony Le**
Sophomore — Data Science, Truman State University
Seeking internships in Data Analytics, Data Engineering, and Data Science.

[![GitHub](https://img.shields.io/badge/GitHub-Profile-black?logo=github)](https://github.com/DungLe-304)
