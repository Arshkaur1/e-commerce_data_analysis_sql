# E-Commerce Data Analysis using SQL & Python

## Project Objective
The objective of this project is to perform an in-depth analysis of an e-commerce dataset using **SQL** and further utilize **Python** for data visualization and advanced analytical tasks.

---

## Dataset Used
- **Dataset:** E-Commerce Dataset

---

# Project Questions

## Basic Queries
- Find the top 10 most frequently purchased products.
- List the number of sellers operating in each state.
- Find the number of products listed in each category.
- Find the total sales per category.
- Calculate the percentage of orders that were paid in installments.

---

## Intermediate Queries
- Calculate the average delivery time (difference between order purchase and delivery) by state.
- Identify the top 5 product categories with the highest return rate.
- Find the relationship between installment payments and order value:
  - Average order value when paid in installments
  - Average order value when paid in full
  - Correlation analysis using Python
- Find the average number of products per order, grouped by customer state.
- Calculate the percentage of total revenue contributed by each product category.

---

## Advanced Queries
- Distribute orders across spend tiers:
  - Very Low
  - Low
  - Medium
  - High
  - Very High
- Find the top 5 sellers' market share in each category.
- Calculate the month-on-month growth rate of total sales.
- Calculate cumulative sales per month for each year.
- Analyze state-wise delivery performance:
  - Early
  - On Time
  - Late

---

# Process

1. Downloaded the dataset archive (`.zip`) and extracted it into a separate folder.
2. Used **Jupyter Notebook** to push the tables into a **MySQL localhost server**.
3. Executed SQL queries using:
   - Joins
   - Filters
   - Common Table Expressions (CTEs)
   - Window Functions
   - Aggregate Functions
4. Ran the same queries in Jupyter Notebook using the `mysql-connector` library and displayed the outputs as Pandas DataFrames.
5. Created visualizations such as:
   - Bar Charts
   - Line Charts
   - Correlation Plots

   using:
   - Matplotlib
   - Seaborn

---

# Technologies Used

- **SQL (MySQL)**
- **Python**
- **Jupyter Notebook**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **mysql-connector-python**

---

# Conclusion

This project demonstrates how **SQL** and **Python** can be used together to perform comprehensive data analysis on an e-commerce dataset. SQL was used for querying, aggregation, and transformation of data, while Python was used for data visualization and additional statistical analysis.
