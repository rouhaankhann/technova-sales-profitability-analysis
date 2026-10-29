# TechNova Sales & Profitability Analysis

## Project Overview

This project analyzes sales and profitability for **TechNova**, a fictional technology retailer selling laptops, monitors, keyboards, and mice across four regions. Using SQL, Excel, Power BI, and DAX, I examined business performance across products, regions, customer segments, salespeople, and months.

The goal was to turn raw sales data into actionable business insights and recommendations for management.

## Business Problem

Management wanted to understand what drives revenue and profit, which products and regions perform best, and where there may be opportunities to improve profitability.

The analysis focused on questions such as:

- Which products contribute the most revenue and absolute profit?
- Which products have the highest profit margins?
- Which regions generate the most revenue and profit?
- How do Consumer and Corporate customers compare?
- How does performance change over time?
- Which opportunities should management investigate first?

## Tools and Skills

- **SQL:** joins, aggregations, conditional calculations, sorting, data-quality checks, ranking, and time-based analysis.
- **Power BI:** data modeling, relationships, interactive reports, slicers, charts, matrices, and KPI cards.
- **DAX:** revenue, cost, profit, profit margin, order count, distinct customer count, average order value, and time-intelligence measures.
- **Excel:** dataset inspection and preparation.
- **Business analysis:** KPI interpretation, insight development, recommendations, and executive reporting.

## Dataset and Data Model

The fictional dataset contains 30 sales transactions and four supporting tables:

- **Sales:** order dates, customer and product IDs, salesperson IDs, regions, quantities, sales amounts, and costs.
- **Customers:** customer names, segments, and cities.
- **Products:** product names and categories.
- **Salespeople:** salesperson names and teams.
- **DateTable:** a continuous calendar for 2026, used for time-based analysis.

I modeled Sales as the fact table, connected to Customers, Products, Salespeople, and DateTable through one-to-many relationships.

## Key Results

### Overall performance

| KPI | Result |
|---|---:|
| Total revenue | ₹1,001,000 |
| Total profit | ₹269,000 |
| Profit margin | 26.87% |
| Total orders | 30 |
| Unique customers | 10 |
| Average order value | ₹33,367 approximately |

### Product performance

| Product | Revenue | Profit | Profit margin |
|---|---:|---:|---:|
| Laptop | ₹605,000 | ₹143,000 | 23.64% |
| Monitor | ₹216,000 | ₹54,000 | 25.00% |
| Keyboard | ₹120,000 | ₹48,000 | 40.00% |
| Mouse | ₹60,000 | ₹24,000 | 40.00% |

Laptops are the largest contributor to revenue and absolute profit. Keyboards and mice have higher margins, although their total revenue and profit contributions are smaller.

### Regional performance

| Region | Revenue | Profit | Profit margin |
|---|---:|---:|---:|
| North | ₹362,000 | ₹98,000 | 27.07% |
| South | ₹287,000 | ₹73,400 | 25.57% |
| West | ₹263,000 | ₹70,100 | 26.65% |
| East | ₹89,000 | ₹27,500 | 30.90% |

North leads in revenue and absolute profit. East has the lowest revenue but the highest regional profit margin in this dataset. This makes East worth investigating for potential growth, although the current data alone cannot establish the size of its market opportunity.

### Monthly performance

March recorded ₹139,000 in revenue and ₹37,600 in profit. This makes it a strong month in the available dataset, but a single year of data is insufficient to conclude that March consistently performs best or that a recurring seasonal pattern exists.

## Recommendations

1. **Protect laptop performance.** Monitor availability and investigate purchasing costs, discounting, and other factors that could improve its profit margin without damaging sales.
2. **Test growth opportunities for keyboards and mice.** Pilot targeted promotions or cross-selling and measure incremental profit and margin after campaign costs.
3. **Investigate East's growth potential.** Examine customer demand, product mix, availability, and costs before committing to a larger expansion.
4. **Improve future analysis.** Collect multiple years of sales history and marketing expenditure to evaluate seasonality and understand marketing effectiveness more reliably.

## Dashboard

The interactive Power BI dashboard includes:

- KPI cards for revenue, profit, margin, orders, customers, and average order value.
- Monthly revenue trend.
- Revenue by region.
- Profit by product.
- Revenue and profit by customer segment.
- A product-by-region matrix.
- Date, region, segment, and product slicers.

The report allows users to investigate overall performance and drill into specific business dimensions.

## Limitations

- The dataset contains only 30 transactions, so findings should be treated as exploratory.
- The data covers only 2026 and cannot establish reliable multi-year seasonality.
- Marketing expenditure and other operating expenses are not available, limiting assessment of campaign effectiveness and overall business profitability.
- The analysis identifies patterns and associations but does not establish their causes.

## Project Outcome

This project demonstrates an end-to-end analytics workflow:

**Business problem → Data preparation → SQL analysis → Data modeling → DAX measures → Interactive dashboard → Business insights → Recommendations**

The project combines technical analytics skills with business interpretation to support more informed decision-making.

*Note: TechNova and its dataset are fictional and were created for learning and portfolio demonstration purposes.*