# amazon-sales-report-analysis

# 📊 E-Commerce Sales Data Analysis Project

This project is an exploratory data analysis (EDA) of an e-commerce sales dataset using Python in Jupyter Notebook. The main goal is to clean the dataset, explore insights, and visualize sales performance using various metrics like revenue, product categories, customer types, regions, and time-based trends.

---

## 🧰 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📁 Dataset

The dataset contains **128,976** orders with the following fields:
- Order ID, Date, Status, Fulfilment, Sales Channel
- Product Category, Size, Qty, Amount
- Shipping details (city, state, country, postal code)
- Order Type (B2B/B2C), Courier Status, etc.

> *Note: Some columns had null values or incorrect data types which were cleaned in the process.*

---

## 🧹 Data Cleaning

Key steps:
- Converted `Date` to datetime format
- Fixed wrong `postal-code` dtype (converted to string)
- Dropped empty columns
- Handled missing or incorrect values
- Filtered irrelevant rows (e.g., cancelled orders, zero quantity)

---

## 📊 Exploratory Data Analysis

The following analyses and visualizations were performed:
- Monthly Revenue Trend
- Total Quantity Sold Over Time
- Sales Distribution by Product Category and Size
- Top Performing Products
- Sales by Region (City & State)
- B2B vs B2C Comparison
- Correlation Heatmap for key numeric features

---

## 📈 Key Insights

- Sales were highest in [Month(s)].
- [Top categories] dominated the product sales.
- Most orders came from [Top States/Cities].
- There was a [strong/weak] correlation between quantity and revenue.
- B2C orders were more prevalent than B2B, etc.

---

## 📂 Project Structure

📦 sales-data-analysis/
├── 📄 README.md
├── 📊 Sales_Analysis.ipynb
├── 📁 data/
│ └── raw_dataset.csv
├── 📁 plots/
│ ├── monthly_sales.png
│ └── category_sales.png

---
