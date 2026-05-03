# Data_Analysis_project_7(Olist database)

This project analyzes the Brazilian E-Commerce Public Dataset (Olist) to uncover key drivers of revenue performance across regions, product categories, and customer behavior.

The business problem focuses on understanding why revenue performance is inconsistent despite overall growth in sales volume, and identifying data-driven strategies to improve profitability and market expansion.

## 🎯 Objectives

The analysis is centered around three core business questions:

Revenue Concentration
How is revenue distributed across products, sellers, and regions?
Is the business overly dependent on specific segments?
Regional Performance
Which regions generate the most revenue?
Where are the biggest growth opportunities based on demand vs population?
Product & Category Effectiveness
Which categories drive revenue vs order volume?
How do pricing, freight, and customer satisfaction impact performance?
🗂️ Dataset
Source: Brazilian E-Commerce Public Dataset by Olist
Time Period: 2016 – 2018
Size: ~110,000 orders
Key Features:
Order details (price, status, timestamps)
Product categories
Customer & seller locations
Reviews and ratings

## 🧹 Data Preparation

Key preprocessing steps included:

Removed freight charges from revenue calculations to focus on product-level performance
Handled missing values:
1,537 products (~1.4%) labeled as "Unknown" category
Identified and handled inconsistencies in delivery timestamps
Created new analytical features:
Revenue per capita (state level)
State penetration rate (% of population purchasing)
Product volume & density metrics

## 📈 Key Insights
Revenue Concentration
Total revenue: $13.22M
São Paulo alone contributes 38% of total revenue
Top category (Health & Beauty) contributes 9.3%, indicating a diversified portfolio
Geographic Imbalance
Seller distribution is more concentrated than customer demand
Indicates logistical centralization and inefficiencies
Category Dynamics
High-volume categories ≠ high-revenue categories
Example:
bed_bath_table → highest orders
health_beauty → highest revenue
Customer Behavior
Average Order Value: $159.83
Freight contributes ~15% to total order value
Customer Satisfaction
Ratings vary significantly (2.5 → 5.0) across categories
Indicates inconsistent product/service quality

## 🚀 Recommendations

Based on the analysis:

Expand beyond São Paulo
Reduce over-reliance on a single region
Target underpenetrated states
Segment category strategy
Optimize high-volume categories for conversion
Invest in high-revenue categories for profitability
Decentralize seller network
Improve delivery efficiency and reduce logistics costs
Improve low-rated categories
Address quality issues to boost customer retention
Optimize freight strategy
Introduce incentives like free shipping thresholds

## 🛠️ Tools & Technologies
SQL – Data extraction and transformation
Python (Pandas, Matplotlib) – Data analysis & visualization
Power BI / Excel (optional) – Dashboarding
Jupyter Notebook – Exploratory Data Analysis

## 📊 Deliverables
Exploratory Data Analysis (EDA)
Business insights & recommendations
Data visualizations (charts & dashboards)
Presentation slides (stakeholder-ready)

## 🧠 Key Takeaway

This project highlights that:

Revenue growth alone is not enough — where it comes from, how it is distributed, and the customer experience behind it are critical to sustainable business performance.
