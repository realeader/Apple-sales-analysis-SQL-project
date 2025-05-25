# Apple-sales-analysis-SQL-project
![apple images](https://github.com/user-attachments/assets/c8016141-411d-43a7-9a27-6e198811efbb)

This project showcases advanced SQL querying techniques through the analysis of a large-scale Apple retail sales dataset containing over 1 million rows. The dataset encompasses detailed information about products, stores, sales transactions, and warranty claims from Apple retail locations worldwide.

By working through a diverse set of questions ranging from fundamental to complex, this project demonstrates proficiency in writing sophisticated SQL queries to extract actionable insights from extensive data.

## Database Schema
The project uses five main tables:

stores: Contains information about Apple retail stores.

store_id: Unique identifier for each store.
store_name: Name of the store.
city: City where the store is located.
country: Country of the store.
category: Holds product category information.

category_id: Unique identifier for each product category.
category_name: Name of the category.
products: Details about Apple products.

product_id: Unique identifier for each product.
product_name: Name of the product.
category_id: References the category table.
launch_date: Date when the product was launched.
price: Price of the product.
sales: Stores sales transactions.

sale_id: Unique identifier for each sale.
sale_date: Date of the sale.
store_id: References the store table.
product_id: References the product table.
quantity: Number of units sold.
warranty: Contains information about warranty claims.

claim_id: Unique identifier for each warranty claim.
claim_date: Date the claim was made.
sale_id: References the sales table.
repair_status: Status of the warranty claim (e.g., Paid Repaired, Warranty Void).

## Project Focus
This project primarily focuses on developing and showcasing the following SQL skills:

Complex Joins and Aggregations: Demonstrating the ability to perform complex SQL joins and aggregate data meaningfully.
Window Functions: Using advanced window functions for running totals, growth analysis, and time-based queries.
Data Segmentation: Analyzing data across different time frames to gain insights into product performance.
Correlation Analysis: Applying SQL functions to determine relationships between variables, such as product price and warranty claims.
Real-World Problem Solving: Answering business-related questions that reflect real-world scenarios faced by data analysts.

## Dataset
Size: 1 million+ rows of sales data.
Period Covered: The data spans multiple years, allowing for long-term trend analysis.
Geographical Coverage: Sales data from Apple stores across various countries.





