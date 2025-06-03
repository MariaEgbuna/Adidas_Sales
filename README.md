# Adidas US Sales

## Dataset Overview
This dataset contains detailed sales information for Adidas products within the United States. It provides a comprehensive view of various aspects of sales operations, including:
* **Retailer Information:** Details about the retailers involved in the sales.
* **Product Details:** Information about the specific Adidas products sold.
* **Sales Figures:** Quantity of units sold and the total revenue generated.
* **Profitability Metrics:** Data related to operating profit and margin.
* **Geographical Data:** Sales broken down by region, state, and city.
* **Sales Method:** How the sales were conducted (e.g., online, in-store).
* **Date Information:** The invoice date for each transaction.

## Data Cleaning Performed (Step 1)
Prior to further analysis, a critical data cleaning step was executed using Microsoft Excel:
* **Issue:** The `Total Sales` column initially contained systematic data entry errors, with many values being ten times higher than the actual product of `Price per Unit` and `Units Sold`.
* **Correction:** For all affected rows, the `Total Sales` value was corrected by dividing it by 10.
* **Result:** The `Total Sales` column is now accurate and consistent, ensuring the integrity of the sales figures for reliable analysis.
