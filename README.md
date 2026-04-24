# Retail Sales Analytics (Python)

## Overview
This project explores a global retail sales dataset to understand how the business is performing across sales, customers, and financial metrics. The goal is to turn raw data into clear insights that can support better decision-making.

The analysis covers the full workflow — from data cleaning and auditing to exploration, forecasting, and customer segmentation.

---

## Key Features
- Data cleaning and validation using Python (Pandas)  
- Exploratory data analysis (EDA) to uncover trends and patterns  
- Financial performance analysis (revenue, discounts, growth)  
- Time series analysis and sales forecasting  
- Customer segmentation using RFM (Recency, Frequency, Monetary)  
- Data quality audit to identify inconsistencies and improve reliability  

---

## Dataset
Global Retail Sales Analytics Dataset (Kaggle):  
https://www.kaggle.com/datasets/faheem113141/global-retail-sales-analytics-dataset  

---

## Project Structure
retail-sales-analysis-python/
│
├── notebook/
│ └── retail_sales_analysis.ipynb
├── data/
│ ├── retail_sales_processed.csv
│ └── customer_segments.csv
├── images/
│ └── (charts and visual outputs)
├── README.md
└── requirements.txt

---

## Data Audit
Before analysis, a structured data audit was performed to check data quality and reliability.

Checks included:
- Missing values and completeness  
- Duplicate transactions  
- Invalid values (e.g. negative quantities or prices)  
- Price validation (Unit Price × Quantity vs Total Price)  

This step helped identify inconsistencies that could affect reporting and ensured the dataset was suitable for analysis.

---

## Key Insights
- Revenue is concentrated in a small number of product categories (Pareto effect)  
- Sales show clear seasonal patterns and differences across days of the week  
- A small group of customers contributes a large share of total revenue  
- Discounts influence sales but need to be managed to protect profitability  
- Sales trends can be used to forecast future performance and support planning  

---

## Sample Visuals

### Financial Analysis
![Financial Analysis](images/retail_financial_analysis.png)

### Sales Forecast
![Sales Forecast](images/sales_forecast.png)

### Customer Segmentation
![Customer Segmentation](images/customer_segmentation.png)

---

## Installation

1. Clone the repository: git clone https://github.com/kingTX95/retail_sale_analytics_python_project.git
2. Install dependencies: pip install -r requirements.txt
3. Open the notebook: Jupyter Notebook

---

## Usage
Open the notebook and run the cells step by step.  
The analysis follows a clear flow:
- Load data  
- Clean and validate  
- Explore and visualise  
- Generate insights and forecasts  

---

## Outputs
- Cleaned dataset: `retail_sales_processed.csv`  
- Customer segmentation: `customer_segments.csv`  
- Visualisations saved in the `images/` folder  

---

## Notes
- This project is designed for learning and portfolio purposes  
- The dataset comes from Kaggle and may contain real-world inconsistencies  
- Data cleaning and validation are key parts of the analysis  

---

## Conclusion
This project demonstrates an end-to-end data analysis workflow using Python, with a focus on real business questions. It shows how data can be cleaned, analysed, and turned into insights that support better decisions in a retail environment.
