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

## Key Insights

### Sales and Profitability

- **Technology Leads in Sales and Profitability** – The Technology category recorded the highest total sales and the highest profit margin at **17.40%**, making it the strongest-performing category in terms of both sales and profitability.

- **2017 Was the Strongest Year** – 2017 achieved the highest total sales, order volume, and total profit across the four-year period. The West and East regions were the major contributors to this performance.

- **Discounts and Profitability** – The analysis revealed a substantial negative relationship between discount levels and profit margins. Higher discounts were generally associated with lower profitability.

### Order and Shipping Operations

- **Standard Class Dominates Order Volume** – Nearly 60% of all orders were processed through Standard Class, making it the most frequently used shipping mode. It recorded the longest average order-to-shipment time at **41.85 days**, despite having a typical transit time of only **5 days**.

- **Standard Class Has the Highest Number of Returned Orders** – Standard Class recorded **168 returned orders**, the highest among all shipping modes. Its larger order volume should also be considered when evaluating its return performance.

- **Same Day Has the Highest Return Rate** – Despite handling only **264 orders**, Same Day recorded the highest return rate at **7.20%**. This warrants further investigation, particularly given its relatively low order volume.

- **Recurring Quarterly Order Pattern** – Order volume generally increased from Q1 through Q4 before declining again at the beginning of the following year. This recurring pattern may indicate seasonal fluctuations in order activity.

- **A Sharp Increase in Returns During Q4 2016** – Q3 2016 recorded **361 orders** with a return rate of **3.32%**. In Q4, order volume increased to **411 orders**, while the return rate more than doubled to **7.06%**. This significant increase warrants further investigation.

- **Same Day Has the Shortest Order-to-Ship Time** – Same Day recorded a median order-to-shipment time of **0 days** and an average of **0.88 days**. This indicates that at least half of Same Day orders were shipped on the same calendar day they were placed.


## Business Recommendations

- **Strengthen the Technology Category's Performance** – Since Technology leads in both total sales and profit margin, the business should evaluate opportunities to maintain its performance through effective inventory management, product availability, and targeted marketing strategies.

- **Review Discounting Strategies** – Given the negative relationship between discount levels and profit margins, the business should reassess its discounting strategies. Establishing discount thresholds and monitoring profitability after discounts may help prevent excessive reductions in margins.

- **Investigate Extended Standard Class Shipping Times** – Standard Class handles nearly 60% of orders and has an average order-to-shipment time of 41.85 days, compared with a median of 5 days. The business should investigate unusually long processing times and identify potential operational bottlenecks.

- **Investigate Same Day Returns** – Despite having the shortest order-to-shipment time, Same Day has the highest return rate at 7.20%. The business should examine returned products, customer segments, and order characteristics to identify possible reasons behind the higher return rate.

- **Monitor Seasonal Order and Return Patterns** – The recurring increase in order volume toward Q4 suggests that the business should prepare inventory and operational capacity ahead of peak periods. The sharp increase in the return rate during Q4 2016 also highlights the need for closer monitoring of returns during high-volume periods.

- **Evaluate Shipping Mode Performance Using Return Rates** – Rather than relying solely on the number of returned orders, the business should compare return rates across shipping modes. This provides a fairer assessment of return performance while accounting for differences in order volume.****
