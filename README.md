# TechNova Sales & Profitability Analysis

**Tools:** SQL | Power BI | DAX | Excel  
**Project Type:** Business Analytics  
**Dataset:** Fictional sales data for portfolio demonstration

## 1. Project Overview

This project analyzes sales and profitability for TechNova, a fictional technology retailer selling laptops, monitors, keyboards, and mice across four regions.

The objective was to transform raw transaction data into meaningful business insights, identify product and regional performance patterns, and recommend actions that management could investigate to improve business performance.

The project demonstrates an end-to-end analytics workflow using SQL for data analysis and Power BI for data modeling, calculations, visualization, and reporting.

## 2. Business Problem

Management wanted to understand which products, regions, customer segments, and salespeople contributed most to revenue and profit.

The analysis aimed to answer the following questions:

- Which products generate the highest revenue and absolute profit?
- Which products have the highest profit margins?
- Which regions perform best in revenue and profitability?
- How do Consumer and Corporate customer segments compare?
- How does revenue change throughout the year?
- Which product-region combinations deserve further investigation?
- What actions could management take based on the findings?

## 3. Tools and Skills

| Tool | Application |
|---|---|
| SQL | Joins, aggregations, business queries, rankings, and data-quality checks |
| Power BI | Interactive dashboards, visualizations, relationships, and data modeling |
| DAX | Financial KPIs, profit margins, average order value, and time intelligence |
| Excel | Dataset inspection and preparation |
| Business Analysis | KPI interpretation, recommendations, and executive reporting |

## 4. Dataset

The dataset contains 30 sales transactions and supporting tables.

| Table | Description |
|---|---|
| Sales | Order dates, customer IDs, product IDs, salesperson IDs, regions, quantities, sales amounts, and costs |
| Customers | Customer names, segments, and cities |
| Products | Product names and categories |
| Salespeople | Salesperson names and teams |
| DateTable | Continuous calendar covering 2026 |

The dataset is fictional and was created for learning and portfolio demonstration.

## 5. Data Modeling

The Sales table was used as the central fact table, connected to four dimension tables:

- Customers
- Products
- Salespeople
- DateTable

One-to-many relationships and single-direction filtering were used to support analysis across the different business dimensions.

The continuous DateTable supported
