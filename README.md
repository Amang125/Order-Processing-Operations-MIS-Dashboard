![Google Sheet](https://github.com/Amang125/Order-Processing-Operations-MIS-Dashboard/blob/main/Screenshot%202026-08-20%20223805.png)

# 📊 Order Processing & Operations MIS Dashboard

An Excel-based **Order Processing & Operations MIS Dashboard** designed to simulate a real-world e-commerce operations environment.

The project focuses on **data entry, data processing, data validation, order tracking, payment monitoring, MIS reporting, and dashboard development** using Microsoft Excel.

---

## 🎯 Project Objective

The objective of this project is to create a structured operations management system that helps track and analyze:

* Customer orders
* Order processing status
* Payment status
* Sales performance
* Sales channels
* Product categories
* Data quality and duplicate records
* Operational KPIs

The project is designed to demonstrate practical skills required for **Data Entry, Data Processing, Back Office, Process Associate, Operations Executive, and MIS Executive** roles.

---

## 🛠️ Tools & Technologies

* **Microsoft Excel**
* XLOOKUP
* SUMIF / SUMIFS
* COUNTIF / COUNTIFS
* Excel Tables
* Data Validation
* Conditional Formatting
* Data Cleaning & Quality Checks
* MIS Reporting
* Dashboard Development

---
![Workbook Structure](https://github.com/Amang125/Order-Processing-Operations-MIS-Dashboard/blob/main/Screenshot%202026-08-20%20223931.png)

## 📁 Workbook Structure

The Excel workbook contains five main sheets:

### 1. Orders_Data

Main operational order database containing:

* Order ID
* Order Date
* Customer ID
* Product ID
* Product Name
* Category
* Quantity
* Unit Price
* Total Amount
* Payment Method
* Payment Status
* Order Status
* Shipping City
* Delivery Date
* Sales Channel
* Processed By

The sheet uses **XLOOKUP** to automatically retrieve product information based on Product ID.

---

### 2. Customer_Master

Customer master database containing:

* Customer ID
* Customer Name
* Gender
* Age
* Phone
* Email
* City
* Customer Type

The master table is used to validate customer IDs and maintain standardized customer information.

---

### 3. Product_Master

Product master database containing:

* Product ID
* Product Name
* Category
* Unit Price
* Stock Available
* Supplier
* Reorder Level

This table is used with XLOOKUP to automate product-related information in the order database.

---
![MIS_Report](https://github.com/Amang125/Order-Processing-Operations-MIS-Dashboard/blob/main/Screenshot%202026-08-20%20223947.png)

### 4. MIS_Report

The MIS report provides operational summaries including:

* Total Orders
* Total Sales
* Delivered Orders
* Processing Orders
* Shipped Orders
* Pending Orders
* Cancelled Orders
* Pending Payments
* Failed Payments
* Average Order Value
* Order Status Analysis
* Payment Status Analysis
* Sales Channel Analysis
* Category-wise Analysis

---

### 5. Dashboard

An interactive management dashboard containing:

* Total Orders KPI
* Total Sales KPI
* Delivered Orders
* Processing Orders
* Shipped Orders
* Cancelled Orders
* Order Status Overview
* Sales Channel Performance
* Category-wise Sales
* Sales by Channel

---

## 📊 Key Project Metrics

The current dataset contains:

| Metric              |   Value |
| ------------------- | ------: |
| Total Orders        |      50 |
| Total Sales         | ₹30,440 |
| Delivered Orders    |      18 |
| Processing Orders   |      14 |
| Shipped Orders      |      14 |
| Cancelled Orders    |       4 |
| Pending Payments    |       6 |
| Failed Payments     |       4 |
| Average Order Value | ₹608.80 |

---

## 🔍 Data Quality & Validation

To improve data accuracy, the project implements several checks:

### Customer Validation

Customer IDs are checked against the Customer Master table using:

`COUNTIF`

Each record is classified as:

* Valid
* Invalid

### Duplicate Order Detection

Duplicate Order IDs are automatically detected using `COUNTIF`.

Records are classified as:

* Unique
* Duplicate

### Data Validation

Dropdown lists are implemented for standardized data entry, including:

* Payment Method
* Payment Status
* Order Status
* Sales Channel
* Processed By

This helps reduce manual data-entry errors.

---

## 📈 Dashboard Insights

The dashboard provides a quick overview of operational performance.

### Order Status

* 18 orders delivered
* 14 orders processing
* 14 orders shipped
* 4 orders cancelled

### Sales Channels

Online is the highest order-volume channel with **24 orders**.

B2B generated significant sales revenue despite having only **5 orders**.

### Product Categories

Electronics generated the highest category sales at **₹23,300**.

---

## 💡 Business Use Case

This project simulates how an Operations or MIS team could use Excel to:

1. Enter and maintain daily order data
2. Validate customer and product information
3. Track order processing status
4. Monitor payment issues
5. Identify duplicate records
6. Generate operational MIS reports
7. Analyze sales performance
8. Provide management with a dashboard for quick decision-making

---

## 🎓 Skills Demonstrated

**Excel & MIS**

* Advanced Excel
* Data Entry
* Data Processing
* Data Validation
* Data Cleaning
* XLOOKUP
* SUMIF
* SUMIFS
* COUNTIF
* COUNTIFS
* Excel Tables
* Conditional Formatting
* MIS Reporting
* KPI Reporting
* Dashboard Development
* Operations Reporting
* Data Quality Checking

---

## 📂 Project Files

* `Order_Processing_Operations_MIS.xlsx`
* `README.md`

---

## 👨‍💻 Author

**Aman Gole**

Aspiring Data Analyst / MIS & Operations Professional

**Skills:** Excel | Power BI | SQL | Python | Data Analysis | MIS Reporting | Dashboard Development


🔗 [LinkedIn](https://www.linkedin.com/in/aman-gole-it125)

---

⭐ If you like this project, consider giving it a star!
