# Operations Analysis and Performance Project

This project analyzes retail sales performance and order operations
using Power BI. The report is designed to provide an overview of
financial performance, regional and category contributions, and
operational indicators related to shipping and product returns.

## Business Questions

1. How are sales and profit performing over time?
2. Which product categories and regions contribute most to sales and
   profit?
3. How does profit margin vary across the business?
4. What is the relationship between discounts and profit margin?
5. How are order volumes changing over time?
6. What is the return rate, and how does it vary by shipping mode?
7. How do shipping days differ across shipping modes?
8. Are there notable quarterly trends in orders and returns?

## Tools used

- Microsoft Power BI Desktop
- Power Query
- Power BI Data Visualization

## Data Cleaning and Preparation

- Assigned appropriate data types to columns, including dates, whole numbers, decimal numbers, and text fields.
- Extracted the year from the Order Date column to support yearly analysis.
- Created a Shipping Days column by calculating the difference between Ship Date and Order Date.
- Created a Month column using the MM-yyyy format for monthly trend analysis.
- Created a numerical Month Sorting column (YYYYMM) to ensure chronological sorting rather than alphabetical sorting.
- Created a Quarter column combining the quarter and year for quarterly analysis.
- Created a numerical Quarter Sorting column to maintain the correct chronological order of quarters.
- Removed an unnecessary duplicate Year column to avoid redundancy.

## Key KPIs

- Total Sales - $2.30M
- Order - 5,009
- Profit - $286.40K
- Profit Margin - 12.47%
- Return Rate - 5.91%
- Delivery days average - 34.61 days
- Shipping days median - 4 days
- Orders Growth - 28.29% (2017 vs previous year)

- 
