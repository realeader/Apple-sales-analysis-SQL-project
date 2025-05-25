
---

# Apple Sales Analysis SQL Project

![Apple Retail](https://github.com/user-attachments/assets/c8016141-411d-43a7-9a27-6e198811efbb)

This project demonstrates advanced SQL querying techniques applied to a large-scale Apple retail sales dataset containing **over 1 million rows**. The dataset includes detailed information about products, stores, sales transactions, and warranty claims from Apple retail locations worldwide.

By addressing a diverse range of questions—from fundamental to complex—this project showcases proficiency in crafting sophisticated SQL queries that extract valuable business insights from extensive data.

---

## Database Schema

The project uses five main tables:

### stores

* **store\_id:** Unique identifier for each store
* **store\_name:** Name of the store
* **city:** City where the store is located
* **country:** Country of the store

### category

* **category\_id:** Unique identifier for each product category
* **category\_name:** Name of the category

### products

* **product\_id:** Unique identifier for each product
* **product\_name:** Name of the product
* **category\_id:** Foreign key referencing `category`
* **launch\_date:** Date when the product was launched
* **price:** Price of the product

### sales

* **sale\_id:** Unique identifier for each sale
* **sale\_date:** Date of the sale
* **store\_id:** Foreign key referencing `stores`
* **product\_id:** Foreign key referencing `products`
* **quantity:** Number of units sold

### warranty

* **claim\_id:** Unique identifier for each warranty claim
* **claim\_date:** Date the claim was made
* **sale\_id:** Foreign key referencing `sales`
* **repair\_status:** Status of the warranty claim (e.g., Paid Repaired, Warranty Void)

---

## Project Focus

This project highlights expertise in:

* **Complex Joins & Aggregations:** Performing multi-table joins and meaningful aggregations.
* **Window Functions:** Utilizing advanced window functions for running totals, ranking, and time-based analyses.
* **Data Segmentation:** Segmenting data across different time frames to analyze product and store performance.
* **Correlation Analysis:** Exploring relationships such as product price vs. warranty claims.
* **Real-World Problem Solving:** Answering practical business questions faced by analysts.

---

## Dataset Overview

* **Size:** Over 1 million rows of sales data
* **Time Span:** Multiple years of historical data for trend analysis
* **Geographical Coverage:** Apple retail locations across various countries worldwide

---
