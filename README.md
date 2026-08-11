# Customer Sales Analysis 

## Project Overview
This project is a comprehensive data analysis workflow designed to uncover customer purchasing patterns, evaluate regional sales performance, and track customer retention. Built entirely in Python using pandas for data manipulation, the project transforms raw transactional data into actionable business insights.

## Core Business Questions Addressed
Through data exploration, cleaning, and advanced aggregation, this analysis provides data-driven answers to the following questions:
1. **Who are our most valuable customers?** (Calculating Customer Lifetime Value and revenue generation).
2. **What products sell best together?** (Market basket and cross-selling analysis).
3. **Which regions have the highest sales?** (Geographic revenue distribution).
4. **What are the seasonal trends?** (Time-series analysis of monthly purchasing behavior).
5. **How can we improve customer retention?** (Calculating baseline churn and retention metrics).

## Technical Stack 
* **Language:** Python 3.x
* **Data Manipulation:** `pandas` (Grouping, merging, pivot tables, datetime extraction)
* **Data Visualization:** `matplotlib`, `seaborn`
* **Environment:** Jupyter Notebook

## Repository Structure 
```text
customer-sales-analysis/
│
├── customer_analysis.ipynb   # Main execution notebook with code and visual outputs
├── sales_data.csv            # Raw transactional sales dataset
├── customer_churn.csv        # Raw customer demographic and subscription dataset
├── requirements.txt          # Python dependencies
├── analysis_report.pdf       # Executive summary and dashboard documentation
└── README.md                 # Project overview and setup instructions

Setup & Installation 
To run this project locally, follow these steps:

Clone the repository:

Bash
git clone [https://github.com/yourusername/customer-sales-analysis.git](https://github.com/yourusername/customer-sales-analysis.git)
cd customer-sales-analysis
Create and activate a virtual environment (Windows):

Bash
python -m venv venv
.\venv\Scripts\activate
Install the required dependencies:

Bash
pip install -r requirements.txt
Launch the Jupyter Notebook:
Open customer_analysis.ipynb in VS Code or run jupyter notebook in your terminal to explore the data pipeline and visualizations.

Key Visualizations
The project includes a comprehensive 4-panel dashboard featuring:

Bar charts detailing Total Revenue by Region

Line graphs mapping Seasonal Sales Trends

Horizontal bar charts ranking Revenue by Product Category

Pie charts visualizing overall Customer Retention Rates
