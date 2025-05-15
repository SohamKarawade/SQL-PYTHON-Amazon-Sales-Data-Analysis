# Amazon Sales Data Analysis Using SQL and Python

---

This project performs an in-depth analysis of Amazon sales data by leveraging SQL queries and Python integration within a Jupyter Notebook. The goal is to uncover key insights about sales performance, customer behavior, product popularity, and revenue trends to support data-driven business decisions.

---

## Project Objective

To analyze and visualize various aspects of Amazon sales data, addressing questions such as:

- What are the top-selling products by quantity and revenue?
- How many orders are placed across different cities and states?
- What is the total revenue generated and its distribution across product categories?
- How does customer spending vary across individuals?
- What are the time patterns in order and delivery dates?
- What percentage of total sales is contributed by each product?

---

## Dataset

The dataset contains the following columns:

- `order_id` — Unique identifier for each order
- `product_name` — Name of the product sold
- `price` — Price of the product
- `quantity` — Number of units sold per order
- `customer_id`, `customer_name` — Customer details
- `order_date`, `delivery_date` — Dates of order placement and delivery
- `payment_method` — Payment method used
- `rating` — Customer product rating
- `category` — Product category
- `city`, `state` — Geographic location of customers

---

## Tech Stack

- **SQL**: For querying and aggregating data
- **Python**: Core programming language for integration and analysis
- **Jupyter Notebook**: Interactive environment combining SQL and Python
- **Pandas**: Data manipulation and cleaning
- **Matplotlib / Seaborn** (optional): Visualization of insights

---

## Analysis Steps

### Data Exploration
- Load and inspect dataset structure and contents
- Identify missing values and handle them appropriately

### SQL Querying
- Basic queries: Retrieve orders, counts, and unique values
- Intermediate queries: Aggregate revenue, top products, city-wise order counts
- Advanced queries: Monthly revenue trends, customer spend analysis, delivery time calculation, and sales percentage by product

### Integration with Python
- Run SQL queries from within Jupyter Notebook
- Load query results into Pandas DataFrames for further analysis or visualization

---

## Key Insights

- Total revenue and product quantity sold provide an overview of business volume
- Certain products and categories dominate sales by quantity and revenue
- Monthly revenue trends reveal peak sales periods
- Customer spending analysis identifies top buyers
- Delivery time metrics help evaluate fulfillment efficiency
- Sales contribution percentages highlight best-performing products

---

## How to Run

1. Import the dataset (`amazon_sales_analysis.csv`) into your preferred SQL database.
2. Execute the provided SQL queries directly or via Python SQL connectors.
3. Use the Jupyter Notebook to combine SQL query results with Python for exploration and visualization.
4. Modify queries as needed to extract further insights.

---
