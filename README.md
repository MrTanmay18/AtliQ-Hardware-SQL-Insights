# AtliQ Hardware Insights – SQL Business Analysis (MySQL)

## Project Overview

This project demonstrates end-to-end SQL-based business reporting and analysis for AtliQ Hardware, a fast-growing computer peripherals company.

As data volume increased, Excel-based reporting became inefficient and error-prone. The organization transitioned to MySQL to enable scalable, automated, and reliable business reporting.

This project simulates real-world business requests and solves them using advanced SQL techniques.

---

## Project Report

Download the full project report:

[Download SQL Project Report](report/AtliQ_Hardware_SQL_Insights.pdf)

---

## LinkedIn Project Post

View the LinkedIn project showcase here:

🔗 https://www.linkedin.com/posts/tanmay-pakori_mysql-project-atliq-hardware-insights-activity-7347618953331970049-cxmM

---

## Business Problem

AtliQ Hardware experienced rapid growth, leading to:

- Large-scale sales data
- Slow Excel-based reporting
- Complex discount structures
- Manual and repetitive analysis

The goal was to build scalable SQL solutions to automate reporting and enable data-driven decision-making.

---

## SQL Concepts Implemented

### 1. User Defined Function (UDF)
- Created a fiscal year function to dynamically derive fiscal year from calendar date.

### 2. Stored Procedures
- Automated product-wise sales reporting.
- Built reusable procedures accepting fiscal year and customer inputs.
- Market classification (Gold / Silver) based on sales thresholds.

### 3. SQL Views
- Created layered views to simplify:
  - Pre-invoice deductions
  - Post-invoice deductions
  - Final Net Sales calculation.

### 4. Net Sales Calculation Logic
Net Sales = Gross Price  
- Pre-Invoice Discounts  
- Post-Invoice Discounts  

### 5. Aggregations & Ranking
- Top 5 Markets by Net Sales
- Top 5 Customers by Net Sales
- Top 5 Products by Net Sales
- Top 10 Markets by % Contribution (Using Window Functions)

### 6. Window Functions
- Calculated percentage contribution of net sales across markets.
- Enabled ranking-based reporting.

---

## Technical Skills Demonstrated

- MySQL
- Complex Joins
- Views
- Stored Procedures
- User Defined Functions
- Window Functions
- Aggregations & Ranking
- Business Logic Implementation
- Query Optimization

---

## Business Impact

This project demonstrates how SQL can:

- Replace inefficient Excel reporting
- Automate recurring business reports
- Improve scalability of data analysis
- Support executive-level decision making
- Enable reusable and modular query design

---

Developed as part of practical SQL business analytics training.
