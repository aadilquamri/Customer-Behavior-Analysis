🛍️ Customer Shopping Behavior Analysis
📊 Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across various product categories.
The goal is to uncover insights into spending patterns, product preferences, and customer segmentation to guide data-driven business decisions.

🧠 Objectives

Understand customer demographics and their purchasing behavior.

Identify high-value customers and spending trends.

Evaluate the impact of discounts and subscriptions on sales.

Visualize key performance indicators through interactive dashboards.

🗂️ Dataset Summary

Rows: 3,900

Columns: 18

Key Features:

Customer demographics: Age, Gender, Location, Subscription Status

Purchase details: Item Purchased, Category, Purchase Amount, Season, Size, Color

Behavior metrics: Discount Applied, Previous Purchases, Review Rating, Shipping Type

Missing Data: 37 values in the Review Rating column (imputed by median rating per category)

🧰 Tech Stack
Component	Tools Used
Data Cleaning & Analysis	Python (pandas, numpy, matplotlib)
Database & Querying	PostgreSQL (SQL)
Visualization	Power BI
Data Storage	CSV / PostgreSQL Database
⚙️ Process Workflow
1. Data Preparation (Python)

Imported dataset and performed exploratory data analysis (EDA).

Handled missing values and standardized column names.

Created new engineered features:

age_group (binned age ranges)

purchase_frequency_days (calculated from purchase dates)

Dropped redundant columns like promo_code_used.

Loaded cleaned data into PostgreSQL for further analysis.

2. Data Analysis (SQL)

Performed business-focused queries such as:

Revenue by Gender – Total revenue comparison (Male vs. Female).

Top Products by Rating – Identified high-performing products.

Subscribers vs. Non-Subscribers – Average spend and revenue difference.

Customer Segmentation – Categorized customers into New, Returning, and Loyal.

Discount & Shipping Analysis – Examined patterns between discounts and shipping types.

3. Dashboard (Power BI)

Developed an interactive dashboard showcasing:

Revenue by category, gender, and age group.

Customer segmentation and loyalty trends.

Product ratings and top-performing items.

Discount and subscription impact analysis.

💡 Key Insights

Subscriptions: Encourage sign-ups by promoting exclusive benefits.

Loyalty Programs: Reward repeat buyers to boost retention.

Discount Strategy: Balance promotional offers with profitability.

Product Marketing: Highlight top-rated and best-selling products.

Targeted Campaigns: Focus on high-spending demographics and express shipping users.

🧾 Results

Discovered that subscribers spend 25% more on average than non-subscribers.

Found age group 25–34 as the most profitable segment.

Identified 5 products with the highest dependence on discounts.

Built an interactive Power BI dashboard for strategic visualization.
