🛍️ Customer Shopping Behavior Analysis
📌 Business Problem Statement

The retail company has observed changes in purchasing patterns across demographics, product categories, and sales channels (online vs. offline).
Management wants to understand which factors—discounts, reviews, seasons, and payment preferences—drive consumer decisions and repeat purchases.

📖 Project Overview

This project analyzes customer shopping behavior using 3,900 retail transactions across various product categories.
The goal is to uncover insights on:

Spending patterns

Customer segments

Product preferences

Subscription behavior

These insights help the retail company make informed decisions that boost sales, improve customer satisfaction, and build long-term loyalty.

🎯 Project Deliverables
1. Data Preparation & Modeling (Python)

Cleaned and transformed raw transactional data

Handled missing values and standardized columns

Engineered new features (age groups, behavior metrics)

Loaded cleaned dataset into SQL for structured analysis

2. Data Analysis (SQL)

Extracted key business insights on revenue, loyalty, and discount patterns

Segmented customers and identified high-value profiles

3. Visualization & Insights (Power BI)

Built an interactive dashboard

Visualized revenue distribution, customer demographics, product performance

Enabled trend exploration using dynamic filters and KPIs

4. Report & Presentation

Summarized major findings

Provided actionable business recommendations

🧰 Tools & Technologies

Python: Pandas, NumPy, Matplotlib

SQL: MS SQL Server

Power BI: Interactive dashboards

Excel: Supplementary data checks

Git & GitHub: Version control and documentation

📊 Dataset Summary

Rows: 3,900 transactions

Columns: 18 features

Key Fields:

Age, Gender, Location

Subscription Status

Item Purchased, Category

Purchase Amount, Season

Discount Applied

Review Rating

Shipping Type

Missing Values:

37 missing review ratings imputed using category-wise median

🔍 Exploratory Data Analysis (Python)

Removed duplicates and normalized column names

Imputed missing values using statistical methods

Created new features (age groups, purchase frequency days)

Eliminated redundant attributes

Loaded final cleaned dataset into SQL

💾 Key Business Questions & SQL Analysis

Revenue by Gender – Male vs. Female revenue contribution

High-Spending Discount Users – Discount users with above-average spending

Top-Rated Products – Top 5 items based on average review score

Shipping Impact – Purchase value comparison by shipping type

Subscribers vs. Non-Subscribers – Spend and revenue comparison

Discount-Driven Products – Most purchased products with discounts

Customer Segmentation – New, Returning, Loyal customers

Top Products per Category – 3 highest-selling items per category

Repeat Buyers & Subscriptions – Frequent buyers vs. subscription rate

Revenue by Age Group – Spend trends across age brackets

📊 Power BI Dashboard Features

Customer demographics: Age, Gender, Subscription Status

Revenue breakdown by category and customer segment

Payment and shipping preference patterns

Discount impact on revenue and sales volume

Top-rated and best-selling products

💡 Key Insights

Female customers generate slightly higher revenue than males

Subscribers spend more and have stronger retention

Express shipping users show higher purchase values

Discounts increase sales volume but reduce margins

Loyal customers contribute the largest share of revenue

🚀 Business Recommendations

Boost Subscriptions: Offer exclusive perks and personalized deals

Reward Loyalty: Implement a tiered loyalty program

Optimize Discounts: Maintain promotional balance to preserve profitability

Promote High-Rated Products: Highlight top-rated items in campaigns

Target Profitable Segments: Focus marketing on high-value customers and express-shipping users
