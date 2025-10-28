# Visualizing-time-series-retail-data
Visualizing-time-series-retail-data
Project Overview

This project performs an exploratory data analysis (EDA) on the Online Retail dataset to uncover key insights into sales trends, top-selling product categories, high-value customers, and overall revenue performance. The analysis helps in understanding business patterns, making informed inventory decisions, and identifying customer behavior for targeted strategies.

Dataset

Source: UCI Machine Learning Repository – Online Retail II Dataset

Contents: Transaction-level data including Transaction ID, Date, Customer ID, Product Category, Quantity, Price per Unit, and Total Amount.

Preprocessing:

Removed cancellations and negative quantities

Dropped missing Customer IDs

Converted date columns to datetime format

Created a Revenue column for analysis

Project Files

sales_analysis.ipynb – Jupyter Notebook containing all analysis, visualizations, and insights.

online_retail.csv – The dataset used for analysis.

Key Analysis Performed

Revenue Trends: Examined monthly and weekly revenue patterns to capture seasonality and short-term spikes.

Category Contribution: Identified top revenue-generating product categories (Clothing, Beauty, Electronics).

Top Customers: Highlighted high-value customers who contribute the most to total revenue.

Average Order Value (AOV): Identified premium buyers with higher spending per order.

Cumulative Revenue: Visualized steady long-term revenue growth over time.

Visualizations Included: Line charts, bar charts, and donut charts summarizing trends and contributions. A video demonstrating the sales data analysis has been provided.
Jupyter Notebook

You can view or run the notebook here:

👉 [**Open Copy of 08-Visualizing_Time_Series_Dataset_Retail_Sales_Data.ipynb**](Copy of 08-Visualizing_Time_Series_Dataset_Retail_Sales_Data.ipynb)

Or open it directly in Google Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/14m990fNa0s8aelrTXlCnJxFBPUcw63yL?usp=sharing)


File: Sales data analysis.mp4
Length: ~2 minutes
Content: Walkthrough of revenue trends, category contribution, top customers, AOV, and cumulative revenue.
Note: The video will download when clicked due to file size limits on GitHub
