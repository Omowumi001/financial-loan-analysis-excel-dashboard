# Pizza Sales Analysis (Python)

## Overview
This project explores a pizza sales dataset using Python to calculate key business KPIs and visualise daily sales trends. The analysis focuses on understanding overall performance (revenue, orders, quantity sold) and how ordering behaviour changes across the days of the week.

## Objectives
- Load and inspect raw pizza sales data
- Compute key performance indicators (KPIs)
- Analyse daily trends for:
  - Total Orders
  - Total Revenue
- Present results using simple, clear visualisations

## Tools & Libraries
- Python
- pandas
- numpy
- matplotlib
- seaborn *(imported)*
- plotly *(imported)*

## KPIs Calculated
The notebook computes:
- **Total Revenue** (sum of `total_price`)
- **Total Pizzas Sold** (sum of `quantity`)
- **Total Orders** (unique count of `order_id`)
- **Average Order Value** (total revenue ÷ total orders)
- **Average Pizzas per Order** (total pizzas sold ÷ total orders)

## Visualisations Included
- **Daily Trend – Total Orders:** bar chart of unique orders by weekday (Mon–Sun)
- **Daily Trend – Total Revenue:** bar chart of total revenue by weekday (Mon–Sun)

## Dataset
Expected file: `pizza_sales.csv`


