# PowerBIMobileSalesDashboard

📊 Project Overview
This Power BI project presents an end-to-end analysis of mobile phone sales data collected across multiple countries and sales channels. 
The dashboard uncovers insights about product performance, customer demographics, regional trends, and sales behavior to support data-driven decision-making for marketing and inventory planning.

🧾 Key Business Questions Answered
Which mobile brands and models are best-sellers?
How do sales trends vary by region, channel, and season?
What are the most preferred product specifications (storage, OS, color)?
What customer segments contribute most to sales?
How are different sales channels performing?
Are there noticeable patterns in payment types and demographics?

🧩 Dataset Features
The dataset contains the following key fields:
Transaction Details: Order Date, Quantity, Unit Price, Revenue
Product Info: Brand, Model, Storage, Color, OS
Customer Data: Age Group, Gender
Sales Geography: Country, Region
Channel Info: Sales Channel (Online, In-store, Partner)
Payment Details: Payment Type

🔧 Process Followed
1. Data Cleaning & Preparation
Removed null/duplicate values
Created new columns (Total Revenue, Sales Month)
Standardized brand names and categories
Created date tables for time intelligence

2. Data Modeling
Star schema with Fact_Sales and multiple dimension tables
Established relationships between date, customer, product, and region
3. DAX Measures
Total Sales, Total Quantity, Average Price
Top-Selling Brand/Model
Customer Segmentation Metrics
Monthly Sales Trend and Channel Performance

4. Dashboard Design
Creative use of button slicers, icons, and bookmarks
Interactive filters by brand, region, channel, and demographics
KPI Cards, Line Charts, Donut Charts, Heatmaps

📌 Dashboard Pages
Sales Overview: Brand performance, revenue trends, and top-selling products
Customer Insights: Age & gender analysis, channel preferences, payment behavior
Regional Performance: Country-wise comparison, map visualization, seasonal trends

📈 Key Insights
📍 Samsung and Apple lead in total sales, with high preference for 128GB models
📍 Online sales dominate, especially in the 25–34 age group
📍 Android OS is more popular in developing regions, while iOS leads in premium segments
📍 Q4 shows peak sales due to seasonal and promotional offers

💡 Recommendations
Increase stock of high-selling models before Q4
Optimize online campaigns targeting 25–34 age group
Tailor offers by region and channel to boost underperforming areas
Introduce EMI options for high-end phones to boost premium segment sales
