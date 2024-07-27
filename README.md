# Sales and Marketing Analytics Dashboard

PowerBi Dashboard Link: 'https://app.powerbi.com/links/NlIMjy7l62?ctid=10d00a63-83c1-479c-a8fd-6e2685526a90&pbi_source=linkShare'

# Overview
This Sales and Marketing Analytics Dashboard is a Power BI project designed to provide insights into sales performance, product line performance, deal size distribution, order status, and geographic sales distribution. This project demonstrates data visualization skills, proficiency in DAX (Data Analysis Expressions), and the ability to extract actionable insights from sales data to support business decision-making.
# Features
1. Dynamic and Interactive Visuals: Utilize Power BI's interactive capabilities to explore data through various filters and slicers.
2. Comprehensive Metrics: Includes KPIs for total sales, average sales, and more to provide a quick overview of business performance.
3. Geographic Analysis: Map visualization to understand sales distribution across different regions.
4. Trend Analysis: Line chart visualizing sales trends throughout the year.
5. DAX Calculations: Advanced DAX queries are used to create custom measures and enhance data analysis capabilities.

# Dataset
The dataset contains the following fields:

#### ORDERNUMBER: Unique identifier for each order.
#### QUANTITYORDERED: Number of units ordered.
#### PRICEEACH: Price of each unit.
#### SALES: Total sales value for each order line.
#### ORDERDATE: Date when the order was placed.
#### STATUS: Current status of the order.
#### PRODUCTLINE: Category of the product.
#### MSRP: Manufacturer's suggested retail price.
#### PRODUCTCODE: Unique code for each product.
#### USTOMERNAME: Name of the customer.
#### COUNTRY: Country where the order was placed.
#### DEALSIZE: Size of the deal (small, medium, large).


# Visualizations
1. Total Sales and Average Sales
Type: KPI Cards
Description: Displays total and average sales to provide an overview of performance.
DAX Measures Used:
Total Sales: Calculated using SUM(SALES).
Average Sales: Calculated using AVERAGEX(SalesTable, SalesTable[SALES]).

3. Product Line Performance
Type: Bar Chart
Description: Highlights sales across different product lines.

4. Deal Size Distribution
Type: Donut Chart
Description: Shows sales distribution by deal size.

5. Order Status
Type: Stacked Column Chart
Description: Visualizes the count of orders by status.

6. Sales Throughout the Year
Type: Line Chart
Description: Trends in monthly sales across the year.

7. Geographic Sales Distribution
Type: Map Chart
Description: Sales distribution across regions.
Getting Started
Prerequisites
Power BI Desktop: Download and install Power BI Desktop to view and interact with the dashboard.

# Insights for Sales and Marketing Strategies

1. Identify Growth Opportunities: By analyzing sales data, the dashboard helps identify new opportunities for growth in different markets and product lines.

2. Optimize Marketing Campaigns: Insights from the dashboard enable the marketing team to evaluate the effectiveness of their campaigns and adjust strategies to target the right audience more effectively.
   
3. Improve Customer Retention: Understanding order status and customer satisfaction can lead to improved customer service and retention strategies.

4. Strategic Decision Making: Data-driven insights support informed decision-making for both short-term and long-term sales and marketing goals.
