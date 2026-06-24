# Task 1-E-Commerce Data Cleaning & Preparation

## Objective
To clean and prepare a raw e-commerce transactional dataset for analysis by identifying and resolving data quality issues.

## Dataset
1,200 rows of e-commerce order data containing columns including Order ID, Date, Customer ID, Product, Quantity, Unit Price, Payment Method, Order Status, Coupon Code and Total Price.

## Tools Used 
Microsoft Excel

## Process
- Checked for duplicate order IDs — none found
- Identified and handled missing values in the Coupon Code column — filled with "No Coupon" to indicate no coupon was used
- Verified date formats were consistent across all rows
- Formatted Unit Price and Total Price columns to 2 decimal places
- Verified Total Price accuracy by checking it matched Quantity × Unit Price for all 1,200 rows — all matched correctly
- Checked text columns (Payment Method, Order Status) for inconsistencies — none found

## Key Finding
The dataset was relatively clean with no duplicates and no critical missing values. The only data quality issue was blank Coupon Code entries which were handled appropriately.

## Outcome
A fully cleaned dataset ready for exploratory data analysis.
