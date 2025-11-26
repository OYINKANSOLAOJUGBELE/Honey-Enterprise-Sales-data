
# 📊 Honey Enterprises — Sales Data Analysis (2023)

This repository contains a full analysis of **Honey Enterprises’ 2023 sales performance**, using a dataset of **1,000 sales transactions**.
The goal is to uncover insights on revenue, profit, sales reps, regions, customer behavior, discount impact, and product category performance.

---

## 📁 Dataset Summary

The analysis is powered by the **`sales_data`** sheet, which contains:

| Column                 | Description                                    |
| ---------------------- | ---------------------------------------------- |
| `Product_ID`           | Unique product identifier                      |
| `Sale_Date`            | Excel date serial for transaction date         |
| `Sales_Rep`            | Sales representative responsible               |
| `Region`               | Region of sale: North, South, East, West       |
| `Sales_Amount`         | Total sale value (numeric)                     |
| `Quantity_Sold`        | Units sold in the transaction                  |
| `Product_Category`     | Food, Furniture, Clothing, Electronics         |
| `Unit_Cost`            | Cost per unit                                  |
| `Unit_Price`           | Selling price per unit                         |
| `Customer_Type`        | New or Returning                               |
| `Discount`             | Applied discount rate                          |
| `Payment_Method`       | Cash, Credit Card, Bank Transfer               |
| `Sales_Channel`        | Online or Retail                               |
| `Region_and_Sales_Rep` | Combined field used for pivoting               |
| `Profit`               | Profit per transaction                         |
| `Sale_Month`           | Month-Year formatted string (e.g., “Feb-2023”) |

Total Rows: **1000**
Total Columns: **16**

---

## 🎯 Project Objectives

### **1️⃣ Data Cleaning**

* Converted Excel serial dates to real dates
* Checked for missing values
* Verified numeric columns (Sales_Amount, Profit, Quantity_Sold)
* Standardized categorical fields (Region, Customer_Type, Payment_Method)
* Validated profit calculations to identify anomalies

### **2️⃣ Feature Engineering**

* Extracted **Month**, **Quarter**, **Year**
* Calculated **Profit Margin (%)**
* Categorized **High/Medium/Low** revenue transactions
* Grouped Sales_Rep by Region

### **3️⃣ Exploratory Data Analysis (EDA)**

Key questions explored:

* Which **regions** generate the most revenue?
* Which **sales reps** outperform others?
* Which **product categories** produce the highest profit?
* Does **discount** reduce profit significantly?
* Are **new** or **returning customers** more valuable?
* What is the monthly sales trend?
* Which **payment methods** do customers prefer?

---

## 📊 Core Insights (From the Dataset)

*(You can replace these with your own findings after full analysis)*

### ⭐ **Top-Level Metrics**

* Total Sales Amount
* Total Profit
* Total Quantity Sold
* Number of New vs Returning Customers
* Best Performing Region

### ⭐ **Top Contributors**

* **Top Sales Rep:** (Based on sum of Sales_Amount)
* **Top Product Category:** (By revenue & profit)
* **Most Used Payment Method:** Cash / Credit Card / Bank Transfer

### ⭐ **Patterns Observed**

* High sales months (e.g., Mar-2023, Aug-2023)
* Region-Sales Rep combinations that drive revenue
* Profit anomalies such as extremely negative values (e.g., -172,074.31)
* Discounts correlating with profit reduction

---

## 📈 Visualizations & Dashboards


Recommended visuals:

* 📅 Monthly Revenue Trend
* 🌍 Sales by Region
* 🧍 Sales Rep Performance Ranking
* 🛒 Sales Channel Comparison (Online vs Retail)
* 🧾 Payment Method Preferences
* 📦 Product Category Contribution
* 💰 Profit Distribution

Dashboards available in `/visuals/` (if added).

---

## 🛠 Tools & Technologies Used

* **Microsoft Excel** — cleaning, pivot tables, charts

---

## 📂 Project Structure

```
📦 Honey-Enterprises-Sales-Analysis
│
├── data/
│   └── Honey Enterprises sales data.xlsx
│
├── analysis/
│   └── EDA.ipynb  (optional)
│
├── visuals/
│   └── charts, dashboards, screenshots
│
└── README.md
```

## 📬 Contact

For collaboration, questions, or improvements, feel free to reach out.(I'm open to learn)
Gmail-- ojugbeletoibat@gmail.com
