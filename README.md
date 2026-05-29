# Superstore Sales & Profit Analysis Dashboard

## Project Overview

This project was developed as part of my Data Analytics learning and internship practice. The main objective of this project is to analyze Superstore sales data and create an interactive Tableau dashboard to understand sales performance, profit trends, customer behavior, and regional performance.

The project combines Data Preprocessing, Exploratory Data Analysis (EDA), and Data Visualization techniques to generate meaningful business insights from the dataset.

---

## Dataset Information

Dataset Used: Sample Superstore Dataset

Number of Records: 9,994

Number of Features: 21

The dataset contains information related to:

* Orders
* Customers
* Products
* Sales
* Profit
* Discounts
* Regions
* Categories
* Shipping Details

---

## Data Preprocessing & EDA

The following preprocessing and exploratory data analysis steps were performed using Python and Pandas:

* Loaded the dataset using Pandas.
* Checked dataset dimensions and structure.
* Analyzed summary statistics using describe().
* Verified missing values in all columns.
* Checked for duplicate records.
* Converted Order Date and Ship Date into datetime format.
* Created Year and Month features from Order Date.
* Exported the cleaned dataset for Tableau visualization.

### Libraries Used

* Pandas
* NumPy
* Matplotlib
* Seaborn

---

## Dashboard KPIs

The dashboard includes the following key performance indicators:

* Total Sales: $2.3M
* Total Profit: $286.4K
* Total Orders: 5,009
* Total Customers: 793

---

## Dashboard Visualizations

### 1. Sales Trend Analysis

A line chart showing monthly sales trends over time to identify growth patterns and seasonal variations.

### 2. Region-wise Sales Performance

A bar chart comparing sales performance across different regions.

### 3. Category-wise Sales Distribution

A pie chart showing the contribution of each product category to total sales.

### 4. Top Products Analysis

A bar chart displaying the highest-selling products.

### 5. Sub-Category Profit Analysis

A profit comparison across different product sub-categories.

---

## Key Insights

* Technology category generated the highest sales contribution.
* West region achieved the highest sales among all regions.
* Sales showed an increasing trend over the years.
* Some sub-categories generated significantly higher profits than others.
* A few products contributed a major portion of overall sales.

---

## Tools & Technologies

* Python
* Pandas
* NumPy
* Tableau Public
* VS Code

---

## GitHub Repository Link: https://github.com/Sanjayduduka45/FUTURE_DS-01Superstore-Sales-Profit-Analysis-Dashboard

## Live Dashboard

View Dashboard Here:
[Tableau Public Dashboard](https://public.tableau.com/views/SupermarketSalesProfitAnalysis/Dashboard1?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

## Conclusion

This project helped me understand the complete workflow of a Data Analytics project, including data cleaning, exploratory data analysis, and dashboard development. The interactive Tableau dashboard provides clear insights into sales and profit performance, helping stakeholders make data-driven business decisions.
