# Amazon Diwali India Sales Analysis (2025)

## Project Overview

This project analyzes customer purchasing behavior and sales performance using the **Amazon Diwali India Sales Dataset (2025)**. The dataset is a synthetic representation of 15,000 e-commerce transactions designed to simulate real-world shopping patterns on Amazon India throughout the year 2025.

The objective of this project is to extract **business-driven insights** related to customer behavior, product performance, payment preferences, delivery efficiency, and customer feedback, with a special focus on the Diwali festive season.

---

## Business Objectives

* Understand customer purchasing behavior and repeat buying patterns
* Identify high-performing and underperforming product categories
* Analyze seasonal sales trends during the Diwali period
* Evaluate payment method preferences and their impact on returns
* Assess delivery success and return rates across Indian states
* Link customer reviews and ratings with product returns

---

## Dataset Description

**Dataset:** Amazon Diwali India Sales Dataset (2025)
**Total Records:** 15,000 transactions

### Key Columns:

* **Order_ID:** Unique identifier for each order
* **Date:** Order placement date
* **Customer_ID:** Unique customer identifier
* **Product_Category:** Main category of the product
* **Product_Name:** Specific product name
* **Quantity:** Units ordered
* **Unit_Price_INR:** Price per unit (₹)
* **Total_Sales_INR:** Total order value
* **Payment_Method:** Mode of payment
* **Delivery_Status:** Delivered / Pending / Returned
* **Review_Rating:** Customer rating (1–5)
* **Review_Text:** Short customer review
* **State:** Delivery state in India
* **Country:** Country of order

---

##  Tools & Technologies Used

* **Python:** Pandas, NumPy, Matplotlib, Seaborn
* **SQL:** PostgreSQL (data storage & querying)
* **Visualization:** Power BI
* **Environment:** Jupyter Notebook

---

## Data Cleaning & Preparation

Key data cleaning steps performed:

* Removed duplicate records
* Handled missing or invalid values
* Ensured correct data types for date and numeric columns
* Verified `Total_Sales_INR = Quantity × Unit_Price_INR`
* Filtered invalid quantities and prices

These steps ensured reliable and analysis-ready data.

---

## Analysis Performed

### 1. Sales & Revenue Analysis

* Total and monthly revenue trends
* Seasonal impact of Diwali sales
* Average Order Value (AOV)
* Category-wise and state-wise revenue contribution

### 2. Customer Purchase Behavior Analysis

* Repeat vs one-time customers
* Customer purchase frequency
* Average spend per customer
* Identification of high-value customers

### 3. Product Performance Analysis

* Top and bottom performing products
* Category-wise sales volume
* Return rates by product category
* Relationship between product ratings and returns

### 4. Payment Method Analysis

* Distribution of payment methods
* Comparison of COD vs online payments
* Return rates by payment method

### 5. Delivery & Operations Analysis

* Delivery success rate
* Return and pending order percentages
* State-wise delivery performance

### 6. Customer Review Analysis

* Average rating per category
* Correlation between low ratings and returns
* Identification of poorly rated, high-return products

---

## Key Insights & Findings

* Electronics and Fashion were the **top revenue-generating categories**
* Sales peaked during **October–November**, highlighting strong Diwali demand
* **Repeat customers contributed a majority of total revenue** despite being fewer in number
* COD orders showed a **higher return rate** compared to online payments
* Products with ratings below 3 had significantly higher return percentages
* Certain states consistently showed higher return and delivery issue rates

---

## Business Recommendations

* Implement loyalty programs to retain high-value repeat customers
* Improve quality checks for high-return product categories
* Encourage online payments through offers to reduce COD-related returns
* Strengthen logistics in states with higher delivery issues
* Use customer ratings to proactively identify and improve weak products

---

## Dashboard Overview (Power BI)

The Power BI dashboard includes:

* KPI cards: Total Revenue, Total Orders, Repeat Customers %, Return Rate
* Monthly sales trend visualization
* Top product categories and states
* Payment method distribution
* Filters for Date, State, and Product Category


---

## Conclusion

This project demonstrates an end-to-end data analysis workflow, combining **data cleaning, SQL analysis, visualization, and business storytelling**. The insights derived can help an e-commerce business optimize customer retention, product offerings, payment strategies, and delivery operations.

---

##  Author

**Anandhu Biju**
Aspiring Data Analyst | Python | SQL | Power BI
