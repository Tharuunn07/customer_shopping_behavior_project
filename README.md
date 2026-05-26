# customer_shopping_behavior_project
Customer Shopping Behavior Analysis – End-to-end data analytics project using 3,900 retail transactions to analyze customer behavior, sales patterns, and product performance using Python, SQL, and Power BI, delivering actionable business insights through an interactive dashboard.

# Dataset Summary
Rows: 3,900
Columns: 18
Key Features:
Customer demographics (Age, Gender, Location, Subscription Status)
Purchase details (Item, Category, Amount, Season, Size, Color)
Shopping behavior (Discounts, Promo Codes, Frequency, Reviews, Shipping Type)
Missing Values: 37 in Review Rating column

# Tech Stack
Python (Pandas, NumPy)
PostgreSQL (SQL analysis)
Power BI (Dashboard)
Jupyter Notebook

# Project Workflow
1. Data Cleaning & Preparation (Python)
Loaded dataset using Pandas
Handled missing values in Review Rating using median per category
Standardized column names (snake_case format)
Feature engineering:
Age grouping (age_group)
Purchase frequency feature
Removed redundant column: promo_code_used
Exported cleaned data to PostgreSQL

2. SQL-Based Analysis
Performed business analysis in PostgreSQL:
Revenue comparison by gender
High-spending discount users
Top-rated products
Shipping type vs spending behavior
Subscription vs non-subscription revenue comparison
Discount-heavy product analysis
Customer segmentation (New, Returning, Loyal)
Category-wise top products
Repeat buyers vs subscription behavior
Revenue by age group

3. Power BI Dashboard
Built interactive dashboard to visualize:
Revenue trends
Customer segments
Product performance
Discount impact
Age and subscription insights

## Business Recommendations
Strengthen subscription programs with better incentives
Introduce loyalty rewards for repeat customers
Optimize discount strategy to balance revenue and margin
Focus marketing on high-value age segments
Promote top-rated and best-selling products


