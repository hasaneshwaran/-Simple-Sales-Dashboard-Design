# Task 8 – Simple Sales Dashboard Design

## Objective

Create an interactive sales dashboard showing performance by product, region, and month using Power BI.

## Dataset

- **File:** Sample - Superstore.csv
- **Columns Used:** Order Date, Region, Category, Sales, Profit

## Tools Used

- Power BI Desktop

## Steps Performed

1. Imported the dataset into Power BI.
2. Checked data types and ensured no major missing values.
3. Created a new column for Month-Year from Order Date using:

   ```powerbi
   MonthYear = FORMAT([Order Date], "MMM-YYYY")
