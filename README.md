# Retail-Sales-Analysis-Online-Retail-Dataset-
📌 Project Overview

This project analyzes an online retail dataset containing transactions from a UK-based e-commerce store.
The goal is to extract business insights through data cleaning, exploratory data analysis (EDA), and advanced techniques such as customer segmentation (RFM), revenue forecasting, and product bundling strategies.

This notebook is designed as a portfolio project to showcase my ability to apply data analysis, visualization, and business intelligence techniques to real-world datasets.

🎯 Objectives

Data Cleaning & Preprocessing

Handling missing values

Removing duplicates

Creating new features such as Revenue

Exploratory Data Analysis (EDA)

Sales trends over time

Top products by revenue and by quantity sold

Top customers and their contribution to revenue

Country-wise revenue distribution

Advanced Analysis

Revenue Forecasting: Predict future revenue using time series modeling.

📊 Dataset Information

Source: Online Retail dataset (publicly available for academic purposes)

Period Covered: 2010–2011

Key Columns:

InvoiceNo → Unique transaction ID

StockCode → Product code

Description → Product name

Quantity → Number of items purchased

InvoiceDate → Date of transaction

UnitPrice → Price per item (£)

CustomerID → Unique customer identifier

Country → Country of customer

🔍 Key Insights

Revenue Trends:

Revenue spikes in August, peaks in November (likely holiday shopping), and drops in December.

Customer Insights:

Top 20 customers contribute ~19% of revenue, indicating a long tail of smaller customers.

Product Insights:

DOTCOM POSTAGE generates the highest revenue.

WORLD WAR 2 GLIDERS ASSTD DESIGNS is the most sold product by quantity.

RFM Segmentation:

Customers segmented into Champions, Potential Loyalists, and At Risk groups.

Forecasting:

Monthly revenue forecasts highlight seasonality and can inform inventory planning.

Product Bundling:

Frequently purchased item sets identified, enabling cross-selling and upselling strategies.

📈 Visualizations

Revenue trend by month

Top countries by revenue

Contribution of top customers (Pie chart: Top 20 vs Rest)

Best-selling products by revenue & quantity

Customer segmentation heatmap

🛠️ Tools & Libraries

Python → Pandas, NumPy

Visualization → Matplotlib, Seaborn

Customer Segmentation → Scikit-learn (RFM scoring, clustering)

Forecasting → statsmodels (ARIMA/Exponential Smoothing)

Product Bundling → mlxtend (Apriori & Association Rules)

Jupyter Notebook for workflow and presentation

🚀 Next Steps

Apply more advanced forecasting models (Prophet, LSTM)

Deploy dashboards using Power BI or Tableau

Automate data pipeline for real-time sales monitoring

📂 Project Structure
📁 retail-sales-analysis
│── 📑 retail_sales_analysis_advanced.ipynb   # Main notebook (EDA + Advanced Analysis)
│── 📑 README.md                              # Project documentation
│── 📂 data/                                  # Dataset (if permitted to share)
│── 📂 visuals/                               # Key plots & charts

🙋 Author

Sunday Victor

💼 Aspiring Data Analyst / AI Enthusiast

🌐 Kaggle Profile - https://www.kaggle.com/sunvic

🐦 Twitter - @sunvic567
