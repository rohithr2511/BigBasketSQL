# 🛒 Big Basket Sales Analysis

## 📌 Project Overview

Big Basket is an online grocery store that offers a wide variety of products. The goal of this project is to analyze **sales trends, product performance, and customer preferences** using **advanced SQL queries**. This analysis helps rank products, identify top-performing categories, compare price differences, and generate dynamic reports.

## 🎯 Problem Statement

To analyze product sales performance and customer preferences using **MySQL's advanced SQL functionalities**, including:

- **Ranking**
- **Lead & Lag Analysis**
- **Subqueries**
- **Views & Stored Procedures**
- **Common Table Expressions (CTE)**

## 🏆 Objectives

✅ **Q1:** Rank products based on their sale price within each category.

✅ **Q2:** Find the next product's sale price for comparison within the same category.

✅ **Q3:** Create a **CTE** to get the **top 5 highest-rated products** for each category.

✅ **Q4:** Create a **view** to simplify querying for product information in the **Beauty & Hygiene** category.

✅ **Q5:** Write a **stored procedure** to update the sale price of a product by its ID.

✅ **Q6:** Create a **CTE** to show the **total sales price per category** and rank them.

✅ **Q7:** Create a **view** to store the **sale price and market price difference** for each product.

✅ **Q8:** Create a **stored procedure** to return products from a specific category and sub-category.

✅ **Q9:** Use a **subquery** to find the **product with the highest sale price** in each category.

✅ **Q10:** Use **CASE** to assign discounts based on the market price of the products:

- **High Discount**: Market price > 500
- **Medium Discount**: Market price between 200-500
- **Low Discount**: Market price < 200

## 🛠️ Technologies Used

- **Database**: MySQL
- **Querying Techniques**: CTEs, Views, Stored Procedures, Subqueries, Window Functions
- **Tools**: SQL Workbench, MySQL CLI


## 🚀 How to Use

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/Big-Basket-Sales-Analysis.git
   ```
2. Import the provided SQL scripts into your **MySQL database**.
3. Run the queries to analyze the sales data.
4. Modify stored procedures and views as needed for custom insights.

## 📈 Expected Insights

- **Top-selling categories** & their rankings.
- **Price comparison** across products.
- **Automated price updates** using stored procedures.
- **Discount strategies** for better pricing.


