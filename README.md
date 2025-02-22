# Myntra-Project
Project Description: Myntra Apparel Analysis
This project focuses on analyzing the Myntra apparel dataset to extract valuable insights into product pricing, discounts, and sales trends. The main goal was to enhance business decisions by cleaning the data, performing calculations, and creating visual reports to identify product discounts, availability, and pricing trends.

Objectives:

Clean and prepare the dataset for analysis.
Perform data analysis to uncover trends and patterns.
Retrieve specific data using lookup functions.
Classify discounts and identify high-discount products.
Tools & Techniques Used:
Microsoft Excel (2021)

Data Cleaning & Preparation:

Removed duplicate entries based on Product_ID.
Standardized the DiscountOffer column using IF formulas.
Filled null values in DiscountPrice using the category-wise average with AVERAGEIFS().
Replaced null SizeOption values with "Not Available".
Data Analysis:

Calculated average original prices for products with ratings above 4 using AVERAGEIF().
Counted products with discounts greater than 50% using COUNTIF().
Counted products available in size "M" using COUNTIF().
Classification:

Created a new column to label discounts as "High Discount" or "Low Discount" using the IF() function.
Data Retrieval & Lookup Functions:

Used VLOOKUP()/XLOOKUP() to find product details (brand, price, rating) based on Product_ID.
Retrieved discount prices using INDEX() and MATCH() functions.
Applied nested XLOOKUP() for dynamic data retrieval based on Product_ID.
Outcome:
The analysis provided key insights into product discounts, availability by size, and pricing trends, which can help in better inventory management and promotional strategy formulation for Myntra's apparel categories.
