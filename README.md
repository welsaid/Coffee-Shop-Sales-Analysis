# Coffee Shop Sales Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Data Sources](#data-sources)
- [Tools Used](#tools-used)
- [Data Cleaning/Preparation](#data-cleaning/preparation)
- [Data Analysis](#data-analysis)
- [Recommendations](#recommendations)
- [Additional Dashboard Images](#additional-dashbaord-images)

### Project Overview

This project aims to construct a comprehensive dashboard that provide insights into the sales peformance of a coffee shop over a period of six months. We want to understand how the business is performing overall in all it's three store locations. By analyzing various aspect of the sales data, we seek to identify trends, define key metrics to quantify business outcome, gain a deeper understanding of the company's performance, and make data-driven recommendations

### Data Sources

The primary dataset used for this analysis is the "coffee_shop_sales.xlsx" file, containing detailed information about each sale made by the company.

### Tools Used

- Power Query: Data Cleaning
- Power BI: Analysis and Dashboard

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:
- Data loading and inspection
- Handling missing values
- Data cleaning and formatting

### Data Analysis

Key Performance Indicators (KPIs)
- Total Sales: **$698,812**
- Total Quantity: **214,170**
- Total Transactions: **149,116**

#### Sales Overview
1. Monthly Sales Analysis
   - Total Sales doubled from **$82K** in January to **$166K** in June, reflecting a significant growth over six months
   - January, February and March recorded the lowest total sales of **$82K**, **$76K** and **$99K** respectively, all falling below the average sales price of **$116.47K**
   - April, May and June have the highest total sales of **$199K**, **$157K** and **$166K** respectively, all exceeding the average sales price of **$116.47K**

2. Sales and Quantity by Store
   - Hell’s Kitchen store had the highest sales of **$237K** (33.84%) among all three stores, followed closely by Astoria, **$232K** (33.23%) and Lower Manhattan, **$230K** (32.92%)
   - Lower Manhattan and Hell’s Kitchen both had the same quantities sold of **71.373** and Astoria store has the lowest quantities sold of **70,991**
    
3. Sales by Product Category
   - Coffee and Tea followed by Bakery generates the highest sales of **$270K**, **$196K** and **$82K** respectively
   - Coffee, Tea and Bakery had total sales which exceeded the average sale price of **$77.65K**
   - Coffee having the highest total sales makes it a strong sales drive for the business
     
4. Product Category (Table)
   - This table provides a detailed data of product categories, offering a comprehensive view of each product category. It includes key information such as the total sales, average unit price and quantity sold of each product category

#### Monthly Sales Analysis
The monthly sales analysis provides a comprehensive view of sales performance for each month in comparison to the previous month, showcasing the growth rate. For us to achieve this, a month needs to be selected on the slicer

1. Sales by Product Category (Latest Month vs. Previous Month)
   - January has no record for previous month sales because sales began on January
   - February had the lowest sales performance with negative growth rate for all product categories
   - March had the highest growth rate, followed closely by April, May and June

2. Sales by Day
   - Sales are highest at the middle of each month, each day sales exceeding the average sales of that month
   - Sales are the lowest towards the ending of each month, each day sales falling below the average sales of that month

#### Customer Behaviour Analysis
1. Peak Sales Time
   - Sales rise from 6 AM, peaking at 10 AM daily for each month
   - After 10 AM, sales decline gradually and stabilizes between 12 PM and 5 PM

2. Products by Sale (Top and Bottom 10)
   - Dark Chocolate Lg is the top product by sale for the months of January, February and April
   - Sustainably Grown Organic Lg is the top product by sale for the months of March, May and June
   - Dark Chocolate is the lowest product by sale from January to June

### Recommendations
Based on the findings, we recommend the following actions:
- Expand Morning Rush Capacity. Since sales peak from 6 AM to 10 AM, consider adding more baristas, self-service kiosks, or express counters during these hours to reduce wait times and handle the rush effectively
- Promote Afternoon Specials. Sales remain uniform between 12 PM and 5 PM, suggesting an opportunity to boost this period with promotions like discounts or combo deals
- Enhance Product Variety. Since Hot Chocolate and Barista Espresso are popular, consider introducing seasonal or limited-time variations of these drinks to maintain interest and attract repeat customers


   
