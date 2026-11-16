# SUPERMART GROCERY SALES ANALYSIS
## Business Analysis Report

**Project Type:** Retail Sales & Profitability Analysis  
**Tools:** Microsoft Excel, Pivot Tables, Charts, Formulas, Data Validation  
**Dataset Period:** 03 January 2015 – 30 December 2018  
**Records Analysed:** 9,994

---

## 1. Project Introduction

The Supermart Grocery Sales Analysis project examines historical grocery transaction data to understand sales performance, profitability, customer purchasing patterns, product-category performance, regional contribution, and discount behaviour.

The purpose of this analysis is to convert raw transaction records into meaningful business information. The findings can help a business monitor performance, identify strong and weak areas, and make more informed decisions about products, customers, regions, and promotional offers.

## 2. Project Objectives

- Calculate overall sales, profit, average transaction value, and profit margin.
- Analyse sales and profit trends across months and years.
- Compare product categories and sub-categories.
- Identify high-performing regions and cities.
- Understand customer contribution and ordering frequency.
- Evaluate discount patterns and their relationship with profitability.
- Present the findings in a structured, easy-to-understand format.

## 3. Dataset Overview

The dataset contains **9,994 transaction records** covering the period from **03 January 2015 to 30 December 2018**.

Key fields used in the analysis include:

| Field | Description |
|---|---|
| Order ID | Unique transaction identifier |
| Customer Name | Customer associated with the transaction |
| Category | Main product category |
| Sub Category | Product sub-category |
| City | City associated with the transaction |
| Order Date | Date of the transaction |
| Year / Month | Time dimensions used for trend analysis |
| Region | Business region |
| Sales | Sales value |
| Discount | Discount rate |
| Profit | Profit value |
| State | State associated with the transaction |

The dataset contains 7 product categories, 23 sub-categories, 24 cities, 5 region labels, and 50 unique customer names.

## 4. Key Performance Indicators (KPIs)

| KPI | Result |
|---|---:|
| Total Sales | ₹14,956,982.00 |
| Total Profit | ₹3,747,121.20 |
| Overall Profit Margin | 25.05% |
| Unique Orders | 9,994 |
| Unique Customers | 50 |
| Average Sales per Record / Order | ₹1,496.60 |
| Average Profit per Record / Order | ₹374.94 |
| Average Discount | 22.68% |

**Calculation definitions**

- Total Sales = Sum of all Sales values.
- Total Profit = Sum of all Profit values.
- Profit Margin = Total Profit ÷ Total Sales × 100.
- Average Sales per Record = Total Sales ÷ Number of Records.
- Average Profit per Record = Total Profit ÷ Number of Records.

In this dataset, each recorded Order ID is unique, so the record-level average is also the average per recorded order.

## 5. Business Analysis

### 5.1 Yearly Sales and Profit Performance

| Year | Total Sales | Total Profit |
|---|---:|---:|
| 2015 | ₹2,975,599.00 | ₹752,529.11 |
| 2016 | ₹3,131,959.00 | ₹797,192.99 |
| 2017 | ₹3,871,912.00 | ₹953,216.22 |
| 2018 | ₹4,977,512.00 | ₹1,244,182.88 |

**Insight:** 2018 was the strongest year in the dataset for both sales and profit. Sales and profit increased across each year shown, indicating an upward trend over the four-year period.

### 5.2 Monthly Sales Performance

| Month | Total Sales | Total Profit |
|---|---:|---:|
| January | ₹577,972 | ₹142,518.52 |
| February | ₹456,102 | ₹116,082.21 |
| March | ₹1,053,980 | ₹267,347.33 |
| April | ₹998,453 | ₹247,476.97 |
| May | ₹1,086,920 | ₹263,643.40 |
| June | ₹1,057,808 | ₹263,296.16 |
| July | ₹1,089,385 | ₹274,594.57 |
| August | ₹1,046,807 | ₹258,912.09 |
| September | ₹2,064,266 | ₹517,788.56 |
| October | ₹1,243,289 | ₹309,376.90 |
| November | ₹2,193,924 | ₹556,048.05 |
| December | ₹2,088,076 | ₹530,036.44 |

**Key observations**

- November recorded the highest total sales: ₹2,193,924.
- February recorded the lowest total sales: ₹456,102.
- November, December, and September were the strongest months by total sales.
- Monthly profit margins remained within a relatively narrow range, from approximately 24.26% to 25.45%.

These are month-of-year totals combined across all four years, not figures for a single year.

### 5.3 Category Performance

| Category | Sales | Profit | Profit Margin |
|---|---:|---:|---:|
| Eggs, Meat & Fish | ₹2,267,401 | ₹567,357.22 | 25.02% |
| Snacks | ₹2,237,546 | ₹568,178.85 | 25.39% |
| Food Grains | ₹2,115,272 | ₹529,162.64 | 25.02% |
| Bakery | ₹2,112,281 | ₹528,521.06 | 25.02% |
| Fruits & Veggies | ₹2,100,727 | ₹530,400.38 | 25.25% |
| Beverages | ₹2,085,313 | ₹525,605.76 | 25.21% |
| Oil & Masala | ₹2,038,442 | ₹497,895.29 | 24.43% |

**Key observations**

- Eggs, Meat & Fish generated the highest category sales.
- Snacks generated the highest category profit.
- Snacks had the highest category profit margin at approximately 25.39%.
- Oil & Masala had the lowest category profit margin at approximately 24.43%, making it a useful category for further cost and pricing review.

### 5.4 Sub-Category Performance

- Health Drinks recorded the highest sub-category sales: ₹1,051,439.
- Health Drinks also generated the highest sub-category profit: ₹267,469.79.
- Health Drinks contributed approximately 7.14% of total business profit.

This makes Health Drinks an important sub-category to monitor for product availability and continued performance.

### 5.5 Regional Performance

| Region | Sales | Profit | Profit Margin |
|---|---:|---:|---:|
| West | ₹4,798,743 | ₹1,192,004.61 | 24.84% |
| East | ₹4,248,368 | ₹1,074,345.58 | 25.29% |
| Central | ₹3,468,156 | ₹856,806.84 | 24.70% |
| South | ₹2,440,461 | ₹623,562.89 | 25.55% |
| North | ₹1,254 | ₹401.28 | 32.00% |

**Key observations**

- West generated the highest sales and profit.
- South had the highest margin among the larger regions shown.
- North contains only one transaction in this dataset. Its 32.00% margin is therefore not a reliable basis for comparing normal regional performance.

### 5.6 City Performance

- Kanyakumari recorded the highest city sales: ₹706,764.
- Vellore recorded the highest city profit: ₹174,073.01.
- Tenkasi had the lowest city profit margin in the city comparison, at approximately 24.27%.
- Kanyakumari had the highest city sales and a profit margin of approximately 24.37%.

City-level performance should be reviewed using both sales and profit margin rather than sales alone.

### 5.7 Customer Analysis

- Krithika generated the highest customer sales: ₹334,361.
- Arutra generated the highest customer profit: ₹87,572.40.
- Amrish placed the highest number of orders: 227.
- Aditi had the highest average sales per order: approximately ₹1,602.53.
- Krithika contributed approximately 2.24% of total sales.
- Average sales per customer across 50 customers were approximately ₹299,139.64.

The customer results show that the highest-sales customer, highest-profit customer, and most frequent customer are not necessarily the same person.

### 5.8 Discount Analysis

- The average discount across transactions was approximately 22.68%.
- Beverages had the highest average category discount at approximately 23.03%.
- Organic Vegetables had the highest average sub-category discount at approximately 23.45%.
- There were 2,334 transactions with discounts of 30% or more. Together, these transactions generated ₹865,883.69 profit, with an aggregate margin of approximately 24.83%.
- Transactions with discounts above 25% generated ₹1,469,165.86 profit, representing approximately 39.21% of total profit.

The aggregate profit margins across populated discount bands were fairly similar (approximately 24.85%–25.23%). Therefore, this dataset does not show a clear, consistent decline in aggregate margin as discount levels increase. Individual high-discount, low-profit transactions should still be reviewed.

## 6. Key Business Insights and Recommendations

1. **Protect strong-performing categories:** Eggs, Meat & Fish leads category sales, while Snacks leads category profit. Track both sales volume and margin when planning inventory.
2. **Review lower-margin categories:** Oil & Masala has the lowest category margin. Review product costs, pricing, and discount decisions in this category.
3. **Plan around strong months:** September, November, and December show higher combined monthly sales. Inventory and promotional planning can take these patterns into account.
4. **Study regional differences:** West is the largest region by sales and profit. Compare product mix and operating factors across regions before making resource decisions.
5. **Monitor customer behaviour:** Krithika, Arutra, and Amrish lead different customer measures. Customer strategies should consider sales, profit, and order frequency together.
6. **Evaluate discounts carefully:** High discount activity does not automatically mean lower aggregate margin in this dataset. Review individual transactions and category-level results before changing discount policy.
7. **Investigate the North-region data:** Since North has only one record, confirm whether the region field is complete and correctly assigned before using it in regional comparisons.

## 7. Excel Concepts Used

The analysis uses or is structured around the following Excel concepts:

- Sorting and filtering transaction data.
- SUM and AVERAGE calculations.
- COUNT and distinct-count analysis.
- Percentage and profit-margin calculations.
- SUMIFS / COUNTIFS-style conditional aggregation.
- Date-based grouping by year and month.
- Pivot-style summaries by category, sub-category, region, city, and customer.
- Discount-band analysis.
- Data validation controls and named ranges for interactive analysis.
- Conditional formatting and data-quality checks.
- Dashboard KPI and chart design.

## 8. Conclusion

The Supermart Grocery Sales Analysis provides a structured view of business performance across 9,994 grocery transactions from 2015 to 2018. The business generated ₹14.96 million in sales and ₹3.75 million in profit, with an overall profit margin of approximately 25.05%.

The analysis identifies the strongest year, sales months, product categories, sub-categories, regions, cities, and customer measures. It also highlights areas that deserve additional review, including the lower margin in Oil & Masala, high-discount transactions, and the single-record North region.

Overall, this project demonstrates how Excel-based analysis can turn raw sales data into practical business insights and support better reporting and decision-making.

---

**Report note:** Figures in this report are based on the Supermart analysis workbook available for this project. Currency values are shown in Indian Rupees (₹). Month-of-year totals combine records from 2015–2018. The North-region result is explicitly qualified because it is based on one transaction.
