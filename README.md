# Customer Shopping Behavior Analysis

## Project Overview

This project analyzes customer shopping behavior using transactional data from 3,900 purchases across multiple product categories. The objective was to uncover spending patterns, customer segments, product performance, and subscription behavior to support data-driven business decisions.

🎯 Business Objectives

Analyze customer spending patterns across demographics and subscriptions

Identify high-value customers and discount-driven products

Segment customers based on purchase behavior

Deliver actionable insights through SQL analysis and Power BI dashboards


📊 Dataset Summary

Records: 3,900 transactions

Columns: 18

Key Attributes:

Customer demographics (Age, Gender, Location, Subscription Status)

Purchase details (Product, Category, Amount, Season, Size, Color)

Behavioral metrics (Discount Applied, Purchase Frequency, Review Rating, Shipping Type)


🧹 Data Cleaning & Preparation (Python)

Loaded and explored data using pandas (info(), describe())

Handled missing values in review ratings using category-wise median imputation

Standardized column names to snake_case

Performed feature engineering:

Created age_group for demographic analysis

Derived purchase_frequency_days for behavioral insights

Removed redundant fields after consistency checks

Loaded the cleaned dataset into PostgreSQL for SQL-based analysis


🧮 Data Analysis (SQL – MySQL)

Conducted SQL analysis to answer key business questions, including:

Revenue comparison by gender and subscription status

Identification of high-spending discount users

Top 5 products by average rating

Spend comparison across shipping types

Customer segmentation into New, Returning, and Loyal groups

Analysis of repeat buyers and subscription adoption

Revenue contribution by age group

Top-performing products within each category


📈 Data Visualization (Power BI)

Developed an interactive Power BI dashboard to visualize:

Revenue trends and customer segments

Product performance and discount dependency

Subscription vs. non-subscription spending behavior

Demographic-based revenue contribution

The dashboard enables stakeholders to filter and explore insights dynamically.


💡 Key Insights & Business Impact

Subscribers generate higher average revenue compared to non-subscribers

Loyal customers contribute a significant share of total revenue

Certain products rely heavily on discounts, impacting margins

Specific age groups and express-shipping users drive higher spend


📌 Business Recommendations

Promote subscription benefits to increase recurring revenue

Introduce loyalty programs to convert repeat buyers into loyal customers

Optimize discount strategies for margin-sensitive products

Focus marketing on high-revenue age groups and top-rated products

🛠 Tools & Technologies

Python (Pandas) • SQL (MYSQL) • Power BI • Excel • Data Cleaning • Data Visualization

🎯 Skills Demonstrated

Data Analysis • SQL Queries • Customer Segmentation • Business Insights • Dashboard Development • Data-Driven Decision Making
