# Product Analytics & Customer Retention Analysis

## Project Overview

This project explores customer behavior and product performance using transactional retail data.
The goal is to simulate product analytics and funnel-style insights without website event data, focusing instead on revenue concentration, customer retention, and cross-selling opportunities.

The analysis follows a business-driven approach.

## Business Questions

This project aims to answer the following questions:

- Which products generate the majority of the company’s revenue?

 - Do customers return after their first purchase?

 - Which products are commonly purchased together?

## Analysis Summary

The project is structured into three main analytical phases:

1.Revenue Analysis (ABC Analysis)
Products are classified into A, B, and C categories based on their contribution to total revenue, helping identify high-impact products.

2.Customer Retention Analysis (Cohort Analysis)
Customers are grouped by their first purchase month to measure retention over time and identify churn patterns.

3.Basket Analysis (Cross-Selling)
Transaction data is used to identify products frequently purchased together, supporting cross-sell and bundling opportunities.

## Key Insights

- A small percentage of products contribute to the majority of total revenue.

- Customer retention drops significantly after the first purchase month, indicating early churn.

- Certain products are frequently purchased together, suggesting opportunities for product bundling.

## Data Source

The dataset used in this project is the Online Retail Dataset, available on Kaggle:

[Online Retail Data Set](https://www.kaggle.com/datasets/vijayuv/onlineretail)

Due to file size limitations, the raw CSV file is not included in this repository.
To reproduce the analysis:

1.Download the dataset from the link above

2.Place the CSV file in the data/ folder

## Tools & Technologies

- Python

- Pandas

- Matplotlib

- Seaborn

- Jupyter Notebook

## Project Structure

```
product-analytics-project/
│
├── data/            # Raw data (not included due to size)
├── notebooks/       # Jupyter notebook with full analysis
│   └── product_analytics.ipynb
├── images/          # Final visual outputs
│   └── product_analytics_dashboard.png
├── README.md
├── requirements.txt
└── .gitignore
```
