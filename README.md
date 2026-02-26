# Retail-Customer-Analytics-By-Using-Python
# Retail Customer Analytics | End-to-End Case Study

![Python](https://img.shields.io/badge/Python-3.9%2B-blue)
![Pandas](https://img.shields.io/badge/Pandas-2.x-green)
![Seaborn](https://img.shields.io/badge/Seaborn-0.13%2B-yellow)
![Matplotlib](https://img.shields.io/badge/Matplotlib-3.x-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)

**Complete Retail Customer 360° Analysis** — Merging, cleaning, EDA, and business insights on 3 years of transactional data for a large retail chain.

Built as part of **AnalytixLabs Case Study 1 - Customer Analysis for Retail**.

---

## 🎯 Business Problem

A leading retail store wants to deeply understand its customers' behavior across locations, product categories, store types, and demographics to optimize marketing, inventory, and customer experience.

**Goal**: Create a single unified dataset (`Customer_Final`) and deliver 11 critical business metrics, reports, and actionable insights.

---

## 📊 Datasets Used

| File                | Description                              | Rows     |
|---------------------|------------------------------------------|----------|
| `Customer.csv`      | Customer demographics (DOB, Gender, City)| ~5,000   |
| `Transactions.csv`  | All customer transactions (2011–2014)    | ~23,000+ |
| `prod_cat_info.csv` | Product hierarchy (Category & Sub-category)| 23     |

---

## ✅ All 11 Business Questions Solved

### 1. Data Preparation
- Merged **Customer + Transactions + Product Hierarchy** → `Customer_Final` (left join to retain all customers)
- Handled data types, date formatting, and negative transactions (returns)

### 2. Summary Report
- Column names & data types
- Top & Bottom 10 observations
- Five-number summary for all continuous variables
- Frequency tables for all categorical variables

### 3. Visual Exploratory Analysis
- Histograms for all continuous variables
- Frequency bar charts for all categorical variables

### 4–11. Key Business Metrics & Insights
4. Time period of transaction data + Count of negative transactions (returns)  
5. Most popular product categories among **Female vs Male** customers  
6. City code with maximum customers + percentage contribution  
7. Store type with maximum sales **by value** and **by quantity**  
8. Total revenue from **Electronics + Clothing** in **Flagship Stores**  
9. Total revenue from **Male** customers in **Electronics** category  
10. Customers with **more than 10 unique transactions** (after removing negative amounts)  
11. For customers aged **25–35 years**:
    - Total amount spent on **Electronics + Books**
    - Total amount spent between **1st Jan 2014 – 1st Mar 2014**

---

## 🔍 Key Business Insights & Recommendations

- **City Code 4** has the **highest number of customers** (≈ 10.5% of total base)
- **Electronics** and **Books** are the most popular categories overall
- **Females** prefer **Clothing** and **Footwear** more than males
- **Males** dominate spending in **Electronics**
- **Flagship Stores** generate the **highest revenue** both by value and quantity
- Customers aged **25–35** spent **₹68,10,777** on Electronics + Books
- In just **Jan–Mar 2014**, the same age group spent **₹6,60,166**
- Significant number of **negative transactions** (returns) — opportunity to reduce return rate
- **10+ unique transaction** customers represent high-value loyal segment

---

## 📈 Visualizations Included in Notebook

- Histograms of `total_amt`, `Qty`, `Rate`
- Bar charts: Product category popularity by Gender
- Bar charts: Store type performance (Value vs Quantity)
- Frequency plots for City Code, Store Type, Product Categories
- Age distribution analysis (25–35 focus)

---

## 🛠️ Tech Stack

- **Python 3.9+**
- pandas, numpy
- matplotlib, seaborn
- Jupyter Notebook

---

## 📁 Repository Structure

```bash
retail-customer-analytics/
├── retail_case_study1.ipynb          # Complete end-to-end analysis
├── Customer.csv
├── Transactions.csv
├── prod_cat_info.csv
├── README.md
└── images/                           
