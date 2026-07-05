# CodeAlpha_DataAnalytics

📊 **CodeAlpha Data Analytics Internship Project**
Tasks Completed: **Task 2 – Exploratory Data Analysis (EDA)** & **Task 3 – Data Visualization**

## 📁 Project Overview

This project analyzes a synthetic **E-Commerce Sales dataset** (2,000+ orders across Jan 2024 – Dec 2025) to uncover sales, profit, and customer behavior trends. Task 2 focuses on exploring, cleaning, and statistically validating the data, while Task 3 turns those findings into a set of clear, decision-ready visualizations.

## 🗂 Repository Structure

```
CodeAlpha_DataAnalytics/
├── data/
│   └── ecommerce_sales.csv              # Dataset used for analysis
├── notebooks/
│   ├── Task2_EDA.ipynb                  # Task 2: Exploratory Data Analysis
│   └── Task3_DataVisualization.ipynb    # Task 3: Data Visualization
├── generate_data.py                     # Script used to generate the dataset
├── requirements.txt
└── README.md
```

## 🛠 Tools & Libraries

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## 🔍 What's Inside Each Notebook

**Task2_EDA.ipynb**
1. Data structure exploration (`info()`, `describe()`)
2. Data quality checks — missing values & duplicate detection/cleaning
3. Univariate analysis of Sales and Profit distributions
4. Statistical validation of the discount → profit relationship
5. Correlation analysis across numeric features
6. Outlier / anomaly detection (IQR method, loss-making orders)
7. Summary of key EDA findings

**Task3_DataVisualization.ipynb**
1. Monthly Sales & Profit trend line chart
2. Category-wise performance (Sales vs Profit dual-axis chart)
3. Regional (pie) and Customer Segment (bar) breakdowns
4. Discount % impact on average profit (bar chart)
5. Payment mode & shipping mode preference charts
6. Correlation heatmap of numeric features
7. Profit distribution & outliers by category (boxplot)
8. Business story summary tying the visuals together

## 📌 Key Insights

- Electronics drives the highest sales volume but has the thinnest profit margin, while Beauty and Fashion deliver stronger margins on lower volume.
- Profit per order declines as discount percentage rises, with 25–30% discounts pushing several orders into a loss.
- Sales and profit show clear month-to-month seasonality rather than flat growth.
- West and North regions contribute the largest share of total sales.
- UPI and Credit Card are the most preferred payment modes; Standard shipping is chosen far more often than Express or Same Day.

## ▶️ How to Run

```bash
pip install -r requirements.txt
jupyter notebook notebooks/Task2_EDA.ipynb
jupyter notebook notebooks/Task3_DataVisualization.ipynb
```

## 🎓 About

Completed as part of the **CodeAlpha Data Analytics Internship**.
