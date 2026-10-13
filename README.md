# Sales Performance Analysis 

## Introduction

This project focuses on analysing sales data to evaluate business performance, identify revenue and profit drivers, and uncover trends across products, regions, customer types, sales representatives, and sales channels.

Using Microsoft Excel, I cleaned and organised the dataset, performed exploratory and descriptive analysis, and developed an interactive dashboard to present key performance indicators and business insights.

The objective was to transform raw sales records into meaningful information that can help management understand business performance, identify opportunities for improvement, and make data-driven decisions.


## Problem Statement
Businesses generate sales data through daily transactions, but raw data alone does not provide a clear understanding of business performance.

Without proper analysis, management may struggle to determine which products generate the most profit, which locations contribute most to operating costs, how sales representatives perform, and how sales activity changes over time.

This project addresses these challenges by analysing sales transactions to identify performance patterns, highlight areas requiring attention, and provide actionable recommendations for improving profitability and sales performance.


## Business Questions
The analysis was guided by the following business questions:

 • What are the company’s total revenue, cost of goods sold (COGS), and profit?
 
 • Which products generate the highest profit?
 
 • Which sales representatives contribute the most to total revenue?
 
 • Which cities account for the highest cost of goods sold?
 
 • How does the number of recorded sales transactions vary across months?
 
 • What insights can these performance indicators provide to support business decision-making?


## Data Source
The dataset used for this project is an Excel sales dataset containing 2,098 sales records and 15 columns.
The dataset includes information on:

 • **Date and Time:** Transaction date and month.
 
 • **Geography:** Region and city.
 
 • **Customer Information:** Customer type, including retail and corporate customers.
 
 • **Sales Channel:** Online and store transactions.
 
 • **Product Information:** Product names and categories.
 
 • **Pricing and Quantity:** Unit price and quantity sold.
 
 • **Sales Performance:** Sales representatives, revenue, cost of goods sold, and profit.
 
 
## Tools Used
### Microsoft Excel
Excel was used throughout the project for:

 • Data cleaning and preparation.
 
 • Formula-based calculations.
 
 • Exploratory data analysis.
 
 • Pivot table analysis.
 
 • Data visualisation.
 
 • Interactive dashboard development.
 
Key Excel features included formulas, PivotTables, charts, and dashboard filtering controls.


## Data Cleaning and Preparation
Before conducting the analysis, I prepared the dataset to improve its consistency and usability.
The preparation process included:

 •  **Data inspection:** Reviewed the dataset structure, column names, data types, and available fields.
 
 •  **Data quality checks:** Examined the records for missing values, duplicates, and inconsistent entries.
 
 •  **Data type validation:** Ensured that dates, prices, quantities, and financial values were represented appropriately.
 
 •  **Calculated fields:** Used formulas to derive cost price, revenue, cost of goods sold, and profit.
 
 •  **Month extraction:** Extracted month names from transaction dates to support monthly analysis.
 
 •  **Data organisation:** Structured the dataset into a consistent tabular format suitable for PivotTables and visualisation.


![image alt](https://github.com/barakatokunlola/Excel/blob/1f1959869f3a5b71178245ad59a588ee7735af86/Sales%20Table.PNG)
Cleaned Dataset


## Data Analysis
I used PivotTables, formulas, and comparative analysis to investigate sales performance across several business dimensions.

### A. Key Performance Indicators
The analysis produced the following headline metrics:
|KPI                        | Result         |
|---------------------------|----------------|
|Total Revenue              | ₦2,328,370,000 |
|Total Cost of Goods Sold   | ₦1,862,696,000 |
|Total Profit               | ₦465,674,000   |
|Number of Sales Records    | 2,098          |
|Profit Margin              | 20%            |

Profit margin was calculated as total profit divided by total revenue.

### B. Product Profitability
Products were compared based on their contribution to total profit to identify the strongest product performers.
The analysis identified **Laptop A13** as the highest-profit product, generating **₦105,336,000** in profit.
This analysis helps management understand which products make the largest contributions to profitability and which products may deserve greater attention in inventory and sales planning.

### C. Sales Representative Performance
Revenue was compared across sales representatives to identify the highest revenue contributors.
**Peter** generated the highest revenue, with **₦434,805,000**.
This comparison provides a basis for evaluating sales performance, identifying effective sales practices, and determining where additional support or training may be useful.

### D. Geographic Cost Analysis
Cost of goods sold was compared across cities to identify locations with the largest cost contributions.
**Lagos** recorded the highest COGS at **₦493,812,000**.
This finding highlights the importance of examining the factors driving costs in different locations before making operational or resource-allocation decisions.

### E. Monthly Sales Activity
Monthly transaction counts were examined to understand how recorded sales activity varied over the period.
**April** recorded the highest number of sales records, with **536**, while **May** recorded the lowest, with **18**.
The unusually low May count warrants further investigation to establish whether it reflects incomplete data, a partial reporting period, or an actual decline in sales activity.

### F. Customer and Sales Channel Analysis
The dataset also supports comparisons by customer type and sales channel.
These dimensions can help management understand differences between retail and corporate transactions and evaluate how online and store-based sales contribute to revenue and profitability.

![image alt](https://github.com/barakatokunlola/Sales-Performance-Analysis/blob/3e0fc1b36fb0d417972409bc87d96825649a40ae/Sales%20PP.PNG)
Pivot Tables and Charts



![image alt](https://github.com/barakatokunlola/Sales-Performance-Analysis/blob/cc0bcc654db098dba2d140b6f82a08f605037a3c/Sales%20Dashboard.PNG))
Sales Dashboard


## Key Insights
The analysis produced the following findings:

**• Strong overall revenue:** The business generated **₦2.328 billion** in revenue across **2,098** sales records.

**• Positive profitability:** Total profit was **₦465.674 million**, representing a **20%** profit margin.

**• Leading product:** **Laptop A13** was the highest-profit product, contributing **₦105.336 million**.

**• Top revenue contributor:** Peter generated **₦434.805 million** in revenue, making him the highest revenue-generating sales representative.

**• Geographic cost concentration:** **Lagos** recorded the highest COGS at **₦493.812 million**, making it an important location for further cost analysis.

**• Uneven monthly activity:** **April** recorded **536** sales records, compared with only **18** in **May**. This substantial difference should be investigated before drawing conclusions about sales performance.


## Recommendations
Based on the findings, the following actions are recommended:

**• Strengthen High-Profit Product Strategies**
Review the sales performance, stock availability, and customer demand for Laptop A13 to understand the factors behind its strong profit contribution. Apply the findings to product planning where appropriate.

**• Investigate Geographic Costs**
Examine the cost drivers behind Lagos’s high COGS. Compare sales volumes, product mix, purchasing costs, and other relevant expenses before deciding whether cost-reduction measures are necessary.

**• Learn from High-Performing Sales Representatives**
Review the sales approaches and customer segments associated with Peter’s revenue performance. Share effective practices with the wider sales team while also considering differences in sales opportunities and assigned responsibilities.

**• Investigate the May Reporting Gap**
Verify the completeness of May’s records and confirm whether the month covers a full reporting period. Resolve any reporting issues before using monthly comparisons to make business decisions.

**• Improve Customer and Channel Strategies**
Compare profitability across retail and corporate customers and between online and store transactions. Use the results to prioritise profitable customer segments and effective sales channels.

**• Monitor Business Performance Regularly**
Use the dashboard to track revenue, COGS, profit, product performance, sales representative contributions, and monthly sales activity. Regular monitoring can help management identify emerging issues and respond promptly.


## Conclusion
This project demonstrates how Microsoft Excel can be used to transform sales transaction data into meaningful business insights.
Through data preparation, formula-based calculations, PivotTable analysis, and dashboard development, I evaluated overall financial performance and identified important patterns in product profitability, sales representative revenue, geographic costs, and monthly sales activity.
The findings provide a starting point for improving product planning, investigating cost drivers, strengthening sales performance, and improving reporting quality.
The project also demonstrates my ability to apply Excel to a complete data analysis workflow, from preparing the dataset to communicating findings through visualisation and business recommendations.
