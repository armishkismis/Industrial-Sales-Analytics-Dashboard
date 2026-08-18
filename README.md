# Industrial Sales Analytics Dashboard

## 📊 Project Overview

This project analyzes industrial sales transaction data using Python and Power BI.

The objective of this project is to clean and analyze sales data, identify important sales and customer trends, and create an interactive Power BI dashboard for business insights.

The project covers the complete data analytics workflow:

- Data cleaning
- Missing value analysis
- Data type handling
- Exploratory Data Analysis
- KPI creation
- Sales trend analysis
- Customer analysis
- Product analysis
- Order status analysis
- Interactive Power BI dashboard

---

## 🎯 Objectives

The main objectives of this project are:

1. Clean and prepare the industrial sales dataset.
2. Identify and handle missing values.
3. Analyze sales and order performance.
4. Identify top-performing products.
5. Analyze customer purchasing behavior.
6. Analyze payment methods and referral sources.
7. Examine order status distribution.
8. Create an interactive Power BI dashboard.
9. Develop meaningful KPIs for business decision-making.

---

## 🗂️ Dataset

The dataset contains industrial sales transaction information.

### Main Columns

| Column | Description |
|---|---|
| OrderID | Unique order identifier |
| Date | Order date |
| CustomerID | Customer identifier |
| Product | Product purchased |
| Quantity | Number of units purchased |
| UnitPrice | Price per unit |
| ShippingAddress | Customer shipping address |
| PaymentMethod | Payment method used |
| OrderStatus | Status of the order |
| TrackingNumber | Shipment tracking number |
| ItemsInCart | Number of items in cart |
| CouponCode | Coupon or promotional code |
| ReferralSource | Source through which customer arrived |
| TotalPrice | Total value of the order |

---

## 🧹 Data Cleaning

Python was used for data cleaning and preprocessing.

The main data preparation steps included:

- Loading the dataset using Pandas
- Checking dataset dimensions
- Checking column data types
- Identifying missing values
- Handling missing values
- Checking duplicate records
- Converting date columns into appropriate date format
- Converting numerical columns into appropriate numeric data types
- Checking inconsistent values
- Preparing the cleaned dataset for analysis

---

## 🐍 Python Analysis

The data analysis was performed using Python.

### Libraries Used

- Pandas
- NumPy
- Matplotlib

Python was used for:

- Data inspection
- Data cleaning
- Missing value analysis
- Descriptive analysis
- Data preparation
- Exploratory analysis

---

## 📈 Power BI Dashboard

An interactive Power BI dashboard was created to visualize the main findings from the dataset.

### Key Performance Indicators

The dashboard includes:

- Total Sales
- Total Orders
- Total Customers
- Total Quantity
- Average Order Value

### Dashboard Visualizations

The dashboard includes:

- Monthly Sales Trend
- Sales by Product
- Quantity Sold by Product
- Payment Method Distribution
- Order Status Distribution
- Sales by Referral Source
- Customer Sales and Order Table
- Yearly Sales Trend

### Interactive Filters

Users can filter the dashboard using:

- Date
- Product
- Payment Method
- Order Status
- Coupon Code
- Referral Source

---

## 💡 Key Insights

The dashboard helps answer questions such as:

- What is the total sales generated?
- Which products generate the highest sales?
- Which products have the highest quantity sold?
- Which payment methods are most commonly used?
- What is the distribution of order statuses?
- Which referral sources generate the most orders?
- How do sales change over time?
- Which customers generate the highest sales?

---

## 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Data cleaning and analysis |
| Pandas | Data manipulation |
| NumPy | Numerical operations |
| Matplotlib | Data visualization |
| Power BI | Interactive dashboard |
| DAX | KPI and measure creation |
| GitHub | Project version control and portfolio |

---

## 📁 Project Structure

```text
Industrial-Sales-Analytics-Dashboard/
│
├── data/
│   ├── raw/
│   │   └── Industrial.csv
│   └── cleaned/
│       └── Industrial_Cleaned.csv
│
├── python/
│   └── Industrial_Analysis.ipynb
│
├── powerbi/
│   └── Industrial_Sales_Dashboard.pbix
│
├── screenshots/
│   └── dashboard.png
│
├── README.md
│
└── .gitignore
