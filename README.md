# 🛒 Superstore Sales — Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-4C72B0)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

---

## 📌 Overview

An end-to-end Exploratory Data Analysis (EDA) project on the Sample Superstore dataset.  
The goal was to answer one key business question:

> **Where is the business making money — and where is it losing it?**

This project covers data cleaning, univariate and multivariate analysis, time-series trends, regional performance, discount impact analysis, and business insight storytelling.

---

## 📊 Key Business Insights

| # | Insight |
|---|---------|
| 1 | **Technology** leads in both sales and profit — it is the core revenue driver |
| 2 | **Furniture** generates strong sales but nearly zero profit — a pricing or cost structure problem |
| 3 | **Tables, Bookcases, and Supplies** are operating at a loss and need urgent review |
| 4 | **Discounts above 20%** consistently push profit into negative territory |
| 5 | **Q4** outperforms all other quarters every year — clear seasonal demand spike |
| 6 | **West region** leads in sales and profit; Central underperforms despite decent sales volume |
| 7 | **Standard Class** is the dominant shipping method (~5 days avg); Same Day is barely used |

---

## 🗂️ Project Structure

```
superstore-eda/
│
├── superstore_eda.ipynb       # Main analysis notebook
├── Sample - Superstore.csv    # Dataset (download from Kaggle)
└── README.md                  # Project documentation
```

---

## 🔍 Analysis Sections

1. **Setup** — Import libraries and configure visualization settings
2. **Load Data** — Read CSV and preview the dataset
3. **Initial Inspection** — Shape, data types, missing values, duplicates
4. **Data Cleaning** — Parse dates, engineer features (ship days, year, quarter)
5. **Univariate Analysis** — Distributions of sales, profit, discount, quantity
6. **Sales & Profit Analysis** — By category and sub-category with profit margins
7. **Time-Series Analysis** — Monthly, yearly, and quarterly sales trends
8. **Regional Analysis** — Sales and profit by region and top 10 states
9. **Discount Impact** — How discounting affects profitability
10. **Correlation Analysis** — Heatmap of numeric feature relationships
11. **Shipping Analysis** — Ship mode usage and average delivery times
12. **Key Business Insights** — Summary of findings and recommendations

---

## 🛠️ Tools & Skills

- **Python** — pandas, numpy, matplotlib, seaborn
- **Data Cleaning** — date parsing, feature engineering, missing value checks
- **Analysis** — univariate, bivariate, time-series, correlation
- **Visualization** — bar charts, histograms, scatter plots, heatmaps, trend lines
- **Business Thinking** — translating data findings into actionable recommendations

---

## 📁 Dataset

- **Source:** [Kaggle — Sample Superstore Dataset](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final)
- **Size:** ~10,000 rows, 21 columns
- **Fields:** Order dates, product categories, sales, profit, discount, region, shipping info

---

## 🚀 How to Run

1. Clone the repo
   ```bash
   git clone https://github.com/YourUsername/superstore-eda.git
   ```
2. Download the dataset from [Kaggle](https://www.kaggle.com/datasets/vivek468/superstore-dataset-final) and place the CSV in the project folder
3. Open `superstore_eda.ipynb` in Jupyter Notebook or [Google Colab](https://colab.research.google.com)
4. Run all cells

---

## 👤 Author

**Mohammad Rahimi**  
Student @ Rochester Institute of Technology — Dubai  
[LinkedIn](www.linkedin.com/in/mohammad-rahimi-2004n) • [GitHub](https://github.com/Nasrawi04)
