# Coffee Sales & Market Potential Analysis

## Overview

This project analyzes sales data for **Monday Coffee**, an online coffee company operating since January 2023.

The objective is to identify the **top three Indian cities for opening new coffee stores** by analyzing customer demand, revenue trends, product performance, and market potential using SQL.

---

## Objectives

* Analyze coffee sales performance
* Estimate coffee consumer demand by city
* Evaluate customer purchasing behavior
* Compare sales against operational costs
* Recommend expansion opportunities

---

## Database Schema

The analysis uses four relational tables:

### city

Stores city information including:

* Population
* Estimated rent
* City rank

### customers

Stores customer information and city mapping.

### products

Stores coffee product catalog and pricing.

### sales

Stores transactions, ratings, and sales information.

---

## Business Questions Solved

### 1. Coffee Consumers Count

Estimate coffee consumers assuming 25% of city population consumes coffee.

### 2. Total Revenue from Coffee Sales

Calculate total revenue generated during Q4 2023.

### 3. Sales Count for Each Product

Measure units sold per product.

### 4. Average Sales Amount per City

Compute average spending per customer.

### 5. Population vs Coffee Consumers

Compare market size across cities.

### 6. Top Selling Products by City

Identify top 3 products using ranking functions.

### 7. Customer Segmentation

Calculate unique customers by city.

### 8. Average Sale vs Rent

Evaluate revenue efficiency and operating economics.

### 9. Monthly Sales Growth

Analyze month-over-month growth.

### 10. Market Potential Analysis

Recommend expansion opportunities.

---

## Final Recommendations

### 🥇 Pune

* Highest total revenue
* Strong average spending
* Low rent burden per customer

### 🥈 Delhi

* Largest estimated coffee consumer market (~7.7M)
* High customer base
* Sustainable rent efficiency

### 🥉 Jaipur

* Highest customer count
* Very low rent per customer
* Strong spending behavior

---

## SQL Concepts Used

* SELECT
* JOIN
* GROUP BY
* HAVING
* CTE
* Window Functions
* DENSE_RANK
* LAG
* Aggregations
* Business KPI Analysis

---

## Tech Stack

* SQL
* CSV Dataset
* GitHub

---

## Project Outcome

Identified high-potential markets for business expansion using data-driven decision making.

Built end-to-end SQL analysis from schema creation to business recommendations.
