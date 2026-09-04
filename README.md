# 🛒 Superstore Sales Dashboard | Microsoft Excel

An interactive Excel dashboard built on the Sample Superstore dataset to analyze sales, profitability, regional performance, customer segments and shipping behaviour.

---

## 🎯 Project Objective

The objective of this dashboard is to analyze Superstore sales performance and provide interactive insights into sales trends, profitability, customer segments, regional and state-level performance, product categories and shipping modes — so that business decisions can be driven by data instead of assumptions.

---

## 📊 Dataset Description

The dataset contains 4 years of retail transaction records (Jan 2014 – Dec 2017) from a US-based Superstore. Each row represents a single product line item within an order and includes sales, profit, discount, quantity, customer, product and shipping details.

**Rows:** 9,994 line items | **Orders:** 5,009 | **Customers:** 793

### Dataset Columns

| Column | Description |
|---|---|
| Row ID | Unique identifier for each row |
| Order ID | Unique identifier for each order |
| Order Date | Date the order was placed |
| Ship Date | Date the order was shipped |
| Ship Mode | Standard, Second Class, First Class, Same Day |
| Customer ID / Customer Name | Customer identifier and name |
| Segment | Consumer, Corporate, Home Office |
| Country / City / State / Postal Code | Location details of the order |
| Region | Sales region (East, West, Central, South) |
| Product ID / Product Name | Product identifier and name |
| Category | Furniture, Office Supplies, Technology |
| Sub-Category | 17 product sub-categories |
| Sales | Sales amount of the line item |
| Quantity | Number of units sold |
| Discount | Discount applied to the order |
| Profit | Profit earned from the line item |

---

## 🧼 Data Cleaning

- Removed duplicate records and blank rows
- Corrected inconsistent **Order Date / Ship Date** formats
- Standardised text fields (Region, Category, Segment, Ship Mode)
- Verified numeric formatting for Sales, Profit, Discount and Quantity
- Maintained a separate **RAW DATA** sheet so the original data stays untouched

### Calculated Fields

- **Month / Year** – extracted from Order Date
- **Profit Margin %** – Profit ÷ Sales
- **Average Order Value** – Total Sales ÷ Total Orders
- **Delivery Days** – Ship Date − Order Date

---

## 📈 Dashboard Features

### KPI Cards
- Total Sales
- Total Profit
- Profit Margin (%)
- Total Orders
- Total Quantity Sold
- Average Order Value
- Average Discount

### Charts
- 📊 Sales by Region
- 📊 Sales & Profit by Category
- 📊 Sales & Profit by Segment
- 📈 Sales vs Profit by Month
- 🚚 Sales & Orders by Ship Mode
- 📍 Top 10 States by Sales

### Interactive Filters (Slicers)
- Year
- Region
- Category
- Segment
- Ship Mode

---

## 🔍 Key Insights

**Overall Performance**
- Total Sales: **$2.30M**
- Total Profit: **$286.4K**
- Profit Margin: **12.5%**
- Total Orders: **5,009**
- Quantity Sold: **37,873 units**
- Average Order Value: **$458.61**
- Average Discount: **15.6%**

**Regional Performance**
- **West** is the strongest region with ~$725K in sales and ~$108K profit.
- **East** follows closely with ~$679K in sales.
- **Central** is the weakest performer — ~$501K in sales but only ~$40K profit (≈8% margin), the lowest of all regions.

**Category Performance**
- **Technology** is the top category in both sales (~$836K) and profit (~$145K).
- **Office Supplies** delivers ~$719K in sales with a healthy ~$122K profit.
- **Furniture** sells well (~$742K) but returns only ~$18K profit (≈2.5% margin) — the biggest problem area.
- Within Furniture, **Tables (−$17.7K)** and **Bookcases (−$3.5K)** are loss-making sub-categories.
- **Copiers, Phones and Accessories** are the most profitable sub-categories.

**Customer Segments**
- **Consumer** contributes the highest sales (~$1.16M, ≈51% of total).
- **Corporate** follows with ~$706K, and **Home Office** with ~$430K.
- Home Office has the best profit margin (~14%) despite the smallest sales volume.

**State Performance**
- **California ($458K)** and **New York ($311K)** together generate about a third of total sales.
- **Texas (−$25.7K)** and **Pennsylvania (−$15.6K)** record heavy losses, mainly due to high discounting.

**Shipping**
- **Standard Class** accounts for ~59% of total sales, making it the most used shipping mode.
- **Same Day** delivery is used least, contributing only ~$128K in sales.

**Trend**
- Sales grew consistently year on year — from **$484K in 2014 to $733K in 2017 (+51%)**.
- **November, December and September** are the peak months; **February** is the weakest.

---

## ❓ Business Questions Answered

1. What are the total sales, profit and profit margin?
2. Which region generates the highest sales and which is least profitable?
3. Which category and sub-categories drive profit — and which lose money?
4. Which customer segment contributes the most revenue?
5. Which states perform best and which are loss-making?
6. Which shipping mode is used the most?
7. How do sales and profit vary month by month?
8. Is the business growing year over year?
9. What is the average order value and average discount?
10. Where is discounting hurting profitability?

---

## 📝 Conclusion

The Superstore Sales Dashboard provides a consolidated view of sales, profitability, regional performance, customer segments and shipping behaviour.

The business generated **$2.30M in sales** and **$286.4K in profit** at a **12.5% margin**, with steady year-on-year growth. However, profitability is uneven: Technology drives most of the profit while Furniture is nearly break-even, and states like Texas and Pennsylvania post losses driven by heavy discounting.

The clearest opportunities are to **review discount policy in loss-making states**, **re-price or rationalise the Tables and Bookcases sub-categories**, and **replicate the West region's playbook in Central**.

---

## 🛠️ Tools & Technologies

- Microsoft Excel
- Pivot Tables & Pivot Charts
- Slicers & Timelines
- Excel Formulas (SUMIFS, INDEX-MATCH, TEXT, IFERROR)
- Data Cleaning
- Dashboard Design
- Data Analysis
---

⭐ If you found this project useful, consider giving the repository a star.
