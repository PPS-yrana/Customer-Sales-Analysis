# Customer Sales Analysis

## Project Overview

Customer Sales Analysis is a Python-based data analysis project developed using **Pandas, NumPy, Matplotlib, and Seaborn**.

The project analyzes sales transactions and customer churn data to understand customer purchasing behavior, sales performance, product performance, regional trends, customer retention, and churn patterns.

The project demonstrates advanced data manipulation techniques using Pandas, including:

- Data cleaning
- Data exploration
- Grouping and aggregation
- Multiple-condition filtering
- String operations
- Datetime operations
- Dataset merging
- Pivot tables
- Customer analysis
- Sales analysis
- Data visualization
- Business insights and recommendations

---

## Project Objectives

The main objectives of this project are:

- Analyze customer purchasing behavior
- Identify the most valuable customers
- Analyze sales performance by product
- Analyze sales performance by region
- Identify monthly sales trends
- Calculate customer spending and lifetime value
- Analyze customer retention
- Analyze customer churn
- Identify frequently purchased product combinations
- Use Pandas aggregation and filtering techniques
- Create pivot tables
- Generate meaningful visualizations
- Provide business recommendations based on the analysis

---

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Programming language |
| Pandas | Data manipulation and analysis |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Seaborn | Statistical visualization |
| Jupyter Notebook | Interactive data analysis |

---

## Datasets

The project uses two datasets.

### 1. Sales Dataset

**File:** `sales_data.csv`

The sales dataset contains information about individual sales transactions.

### Columns

| Column | Description |
|---|---|
| `Date` | Date on which the sale occurred |
| `Product` | Product purchased |
| `Quantity` | Number of units purchased |
| `Price` | Price per unit |
| `Customer_ID` | Unique customer identifier |
| `Region` | Region associated with the sale |
| `Total_Sales` | Total value of the transaction |

The dataset contains **100 sales records and 7 columns**.

---

### 2. Customer Churn Dataset

**File:** `customer_churn.csv`

The customer churn dataset contains information about customer subscriptions and churn behavior.

### Columns

| Column | Description |
|---|---|
| `CustomerID` | Unique customer identifier |
| `Tenure` | Number of months the customer has been with the company |
| `MonthlyCharges` | Monthly amount charged to the customer |
| `TotalCharges` | Total amount charged to the customer |
| `Contract` | Customer contract type |
| `PaymentMethod` | Customer payment method |
| `PaperlessBilling` | Indicates whether paperless billing is enabled |
| `SeniorCitizen` | Indicates senior citizen status |
| `Churn` | Indicates whether the customer has churned |

The dataset contains **500 customer records and 9 columns**.

---

## Project Structure

```text
Customer-Sales-Analysis/
│
├── customer_analysis.ipynb
│
├── sales_data.csv
├── customer_churn.csv
│
├── analysis_report.pdf
├── requirements.txt
├── README.md
│
└── screenshots/
    ├── data_exploration.png
    ├── customer_analysis.png
    ├── pivot_table.png
    ├── sales_dashboard.png
    └── churn_analysis.png
