# Customer Value-Driven Inventory Forecasting in E-Commerce Using Machine Learning

## Overview
This project analyzes e-commerce transaction data to support customer value analysis, demand understanding, and inventory planning decisions. The project combines exploratory data analysis, customer segmentation, Customer Lifetime Value (CLTV) modeling, product demand analysis, and machine learning-based forecasting.

The goal is to connect customer behavior with product demand so that an e-commerce business can make better decisions about inventory prioritization, customer targeting, and revenue planning.

## Business Problem
E-commerce businesses often face challenges in understanding which customers drive the most value, which products should be prioritized, and how customer behavior can inform future demand. Poor inventory planning can lead to stockouts, overstocking, and missed revenue opportunities.

This project answers the question:

**How can customer purchasing behavior and transaction history be used to support customer value prediction and inventory forecasting?**

## Project Objectives
- Clean and validate e-commerce transaction data.
- Analyze customer behavior using transaction frequency and revenue.
- Identify product and customer revenue concentration using Pareto analysis.
- Study return behavior and high-return products.
- Build RFM-based customer segmentation.
- Estimate Customer Lifetime Value using machine learning models.
- Explore demand patterns to support inventory planning decisions.

## Dataset
The notebook is built using an Online Retail / Online Sales transaction dataset.

Key fields used include:
- Invoice
- StockCode
- Description
- Quantity
- InvoiceDate
- Price
- Customer ID
- Country

The dataset itself is not included in this repository. Add your own dataset locally in the `data/` folder if you want to reproduce the analysis.

## Methods Used
- Data cleaning and missing value handling
- Revenue calculation
- Return transaction analysis
- Product-level Pareto analysis
- Customer-level Pareto analysis
- Monthly sales trend and seasonality analysis
- Product demand consistency analysis
- RFM segmentation
- CLTV prediction
- Regression model evaluation
- Machine learning model comparison

## Tools & Technologies
- Python
- Jupyter Notebook / Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- LightGBM

## Key Findings
- The cleaned dataset contains more than 800,000 purchase transactions after removing missing customer IDs, missing descriptions, returns, and cancellations.
- Customer behavior is highly skewed, with a small group of customers contributing a large share of revenue.
- Product revenue follows a Pareto pattern, where a relatively small set of products contributes most of the sales.
- Return rate is low overall, but certain products show high returned-unit volume.
- RFM segmentation helps classify customers into groups such as high-value, loyal, at-risk, and lost customers.
- CLTV modeling provides a way to estimate future customer value and support targeting decisions.

## Repository Structure
```text
customer-value-inventory-forecasting-ecommerce/
│
├── README.md
├── requirements.txt
├── .gitignore
├── notebooks/
│   └── customer_value_inventory_forecasting_ecommerce.ipynb
├── data/
│   └── README.md
├── visuals/
│   └── README.md
├── reports/
│   └── README.md
└── src/
    └── README.md
```

## How to Run
1. Clone or download this repository.
2. Open the notebook in Jupyter Notebook or Google Colab.
3. Place the dataset in the `data/` folder or update the file path in the notebook.
4. Install the required libraries:

```bash
pip install -r requirements.txt
```

5. Run the notebook cells in order.

## Notes
- The notebook was originally developed in Google Colab.
- Update the dataset path before running locally.
- The repository does not include private or large raw data files.

## Author
Janaki S  
MS Data Science, University of Memphis  
Data Science | Machine Learning | Retail Analytics | Customer Analytics
