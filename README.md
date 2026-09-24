# 🌐 Global Electronic Retailer

---

## Project Overview

This project explores sales data from a global electronics retailer operating across multiple countries and sales channels, with transactions covering both Online and In-Store sales.

The analysis focuses on overall sales performance, revenue trends, Online vs. In-Store sales, delivery time, product performance, and customer performance.

The data was cleaned and prepared using **Excel** before being analyzed and visualized in **Power BI** to create an interactive dashboard.

The dashboard is divided into two main sections:

- **Sales Performance** — Provides an overview of sales performance, revenue trends, sales channels, country performance, and delivery time.
- **Product & Customer Analysis** — Examines product performance and customer performance.

---

## Business Questions

This project aims to answer the following questions:

1. What types of products does the company sell, and where are customers located?
2. How has revenue and order volume changed over time?
3. Are there any seasonal patterns or trends in order volume and revenue?
4. How do Online and In-Store sales compare?
5. Is there a difference in Average Order Value (AOV) between Online and In-Store sales?
6. Which countries generate the most In-Store revenue?
7. How does sales performance differ across sales channels?
8. Which product categories and subcategories generate the most revenue?
9. How long is the average delivery time, and has it changed over time?
10. Which customers contribute the most to overall sales performance?

---

## Dataset

The dataset contains information about:

### Sales
- Order Number
- Line Item
- Order Date
- Delivery Date
- CustomerKey
- StoreKey
- ProductKey
- Quantity
- Currency Code

### Customers
- CustomerKey
- Gender
- Name
- City
- State Code
- State
- Zip Code
- Country
- Continent
- Birthday

### Products
- ProductKey
- Product Name
- Brand
- Color
- Unit Cost USD
- Unit Price USD
- SubcategoryKey
- Subcategory
- CategoryKey
- Category

### Stores
- StoreKey
- Country
- State
- Square Meters
- Open Date

### Exchange Rates
- Date
- Currency
- Exchange

---

## Tools

- **Power BI** — Data modeling, DAX, analysis, and dashboard development
- **Power Query** — Data preparation and transformation
- **Excel** — Source data review and preparation

---


## Analysis Approach

### 1. Data Preparation

- Reviewed and selected relevant tables and fields from the source dataset.
- Prepared sales, product, and customer data for analysis.
- Connected related tables using appropriate keys.
- Created calculated columns and measures required for the analysis.

### 2. Sales Analysis

- Calculated Revenue, Cost, Profit, Orders, Quantity Sold, and Average Order Value.
- Analyzed yearly revenue and order trends.
- Compared Online and In-Store sales performance.
- Analyzed In-Store revenue by country.
- Calculated average delivery time based on Order Date and Delivery Date.

### 3. Product Analysis

- Analyzed revenue across product categories, brands and subcategories.
- Identified top-performing products by revenue.
- Compared product performance using Revenue, Profit, Orders, and Quantity Sold.
- Used Top N analysis to highlight high-performing products, brands, categories and subcategories.

### 4. Customer Analysis

- Analyzed the total number of customers and customer purchasing activity.
- Calculated average orders per customer.
- Reviewed customer-level Revenue, Profit, Orders, and Quantity Sold.
- Explored customer information such as country, city, and gender.

### 5. Dashboard Preview

The final Power BI dashboard consists of two pages:

#### Sales Performance

<img width="1350" height="761" alt="image" src="https://github.com/user-attachments/assets/e1238dc0-7c6b-42c7-83a5-bd01c1fe905b" />

#### Product & Customer Analysis

<img width="1350" height="758" alt="image" src="https://github.com/user-attachments/assets/15341798-4a14-4234-abed-fb63d92d5570" />

---

## Key Insights

- The dataset contains approximately **62.9K orders**, **197.8K units sold**, **15,266 customers**, and **2,517 products**.
- Total revenue is approximately **$55.8M**, with approximately **$33M in profit**.
- **In-Store sales account for around 80% of total revenue**, while Online sales contribute around 20%.
- Revenue increased substantially from 2017 through 2019, reaching its highest level in **2019**, before declining in the following years.
- The **United States** generates the highest In-Store revenue among the countries shown, followed by the United Kingdom and Germany.
- **Computers** is the highest-revenue product category, followed by Home Appliances.
- Average delivery time for Online sales decreased from around **8 days in 2016 to 4 days in 2021**.
- Customers place approximately **4.12 orders per customer** on average.

---

## 🔗 Source

Dataset from **Maven Analytics Data Playground**:

https://mavenanalytics.io/data-playground/global-electronics-retailer

---

> **Note:** This project uses selected data from a Maven Analytics dataset and was created for practice and portfolio purposes. The project focuses on applying data preparation, data modeling, DAX, visualization, and business-oriented analysis using Power BI.
