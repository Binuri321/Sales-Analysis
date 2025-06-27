# Sales Analytics Dashboard

# Introduction
This project presents a comprehensive sales analytics dashboard designed to help business leaders understand sales performance, customer trends, and product demand across multiple years. Built using Excel, SQL, and Power BI, the dashboard provides actionable insights to support strategic decision-making and performance tracking.

# Dataset Information
- Source: Company sales database [https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms]
- Contents: Sales transactions from 2019 to 2021, including fields for order date, product name, category, sub-category, customer name, customer city, and sales amount.


# Business Problem
- Are we meeting or exceeding our sales targets?
- Which products, customers, and cities contribute most to sales?
- How do sales trends compare to budgeted targets over time?
- Who are our top customers and what are their purchasing patterns?
- How can we use these insights to drive growth and improve strategy?

# Data Cleaning
- Tools Used: SQL Server for data structuring and cleaning.
- Steps:
  - Removed duplicate records and standardized product/customer names.
  - Addressed missing or inconsistent data in dates and sales amounts.
  - Calculated total sales per product and per customer.
  - Ensured all date fields were in a consistent format for time-series analysis.


# Analysis
- SQL: Used to aggregate sales by product, customer, city, and month; calculate top performers; and compare actual sales to budgeted amounts.
- Power BI: Used for data modeling, DAX calculations, and interactive dashboard creation.
- Key Metrics:
  - Total sales vs. budget by month and year
  - Sales by product category and sub-category
  - Top 10 customers and products by sales
  - Sales distribution by city

# Visualizations
- KPI Cards: Show total sales and budget.
- Bar Charts: Display sales by product category, sub-category, and top customers/products.
- Line Charts: Track monthly sales and budget trends.
- Maps: Visualize sales distribution by customer city.
- Tables: List detailed sales by customer and product for drill-down analysis.
  

# Key Findings
- Sales Performance: Achieved total sales of 22,239,730, exceeding the budget of 21,100,000 by 1,139,730.
- Product Insights: "Bikes" category dominates sales (95%+), with Mountain and Road bikes as top products.
- Customer Insights: Top 10 customers each contributed between 10K and 16K in sales, indicating a strong core customer base.
- Geographic Trends: Sales are concentrated in a few key cities.
- Monthly Trends: Sales generally meet or exceed budget, but there are fluctuations that suggest opportunities for seasonal promotions or inventory planning.

# Business Recommendations
- Focus on Bestsellers: Continue to prioritize the Bikes category and top-selling models for promotions and inventory.
- Strengthen Customer Relationships: Target top customers with loyalty programs and exclusive offers to increase retention and upsell opportunities.
- Expand in High-Potential Cities: Invest in marketing and logistics in cities with strong sales to further grow market share.
- Monitor Seasonal Trends: Use monthly sales insights to plan campaigns and manage stock for peak periods.
- Address Underperforming Products: Review strategy for accessories and lower-selling categories to improve or replace offerings.


# Credits
- Dataset: Simulated company sales data[https://learn.microsoft.com/en-us/sql/samples/adventureworks-install-configure?view=sql-server-ver15&tabs=ssms)]
- Tools: SQL Server, Power BI


