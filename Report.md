# Retail Sales Analysis Report

## Data Understanding and Cleaning

### Completeness and Correctness
The dataset contains 13 entries with the following columns:

- **Order ID**: Unique identifier for each order.
- **Region**: Geographic region of the sale.
- **Product Category**: Type of product sold.
- **Sales Amount**: Total revenue from the sale.
- **Cost**: Cost of the product.
- **Profit**: Difference between sales amount and cost.
- **Order Date**: Date of purchase.
- **Customer Segment**: The type of customer (Consumer, Corporate, Small Business).

All columns have **complete data** with no missing values.

### Handling Outliers and Data Types
- The **Order Date** column was converted to a datetime format.
- A new column **Profit Margin** was calculated using:  
  \[ Profit Margin = Profit / Sales Amount \]
- No extreme outliers were detected within the given dataset.

## Data Summarization

### Sales and Profit by Region
| Region | Total Sales | Total Profit | Avg Sales |
|--------|------------|-------------|------------|
| North  | 4800       | 1350        | 1200.00    |
| East   | 3200       | 900         | 1066.67    |
| South  | 3700       | 800         | 1233.33    |
| West   | 4100       | 950         | 1366.67    |

- **Top performing region**: North (Highest total profit: 1350)
- **Lowest performing region**: South (Lowest total profit: 800)

### Sales and Profit by Product Category
| Product Category | Total Sales | Total Profit | Avg Profit Margin |
|-----------------|------------|-------------|------------------|
| Electronics     | 8900       | 2200        | 0.252            |
| Furniture      | 3600       | 1000        | 0.289            |
| Office Supplies| 3300       | 800         | 0.246            |

- **Most profitable category**: Electronics (Total profit: 2200)
- **Best profit margin**: Furniture (Avg profit margin: 0.289)

## Trend Analysis

### Sales by Customer Segment
| Customer Segment  | Total Sales | Total Profit |
|------------------|------------|-------------|
| Consumer        | 4600       | 1150        |
| Corporate      | 7500       | 2050        |
| Small Business | 3700       | 800         |

- **Most profitable segment**: Corporate (Total profit: 2050)
- **Least profitable segment**: Small Business (Total profit: 800)

### Sales Trend by Order Date
- The most sales are made in the beginning of June and lowers in July, so the data unfortunately is not enough to make any decisions.
- However, Electronics and Corporate segments consistently perform well.

## Insights and Recommendations

### Key Findings
- **North** is the top-performing region, while **South** needs improvement.
- **Electronics** has the highest total profit, but **Furniture** has the best profit margin.
- **Corporate customers** contribute the most to revenue and profit.

### Actionable Recommendations
1. **Expand marketing in the South region** to improve profitability.
2. **Focus promotions on Furniture** as it has the highest profit margin.
3. **Target Corporate customers** with special offers, as they generate the most revenue.
4. **Monitor seasonal trends** to optimize inventory and pricing strategies.


