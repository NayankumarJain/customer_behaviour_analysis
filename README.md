Customer Shopping Behavior Analysis 🛍️
1. Project Overview
This project focuses on analyzing customer purchasing patterns to help a retail business make data-driven decisions. As a Data Analyst, I processed a dataset of 3,900+ customers to identify which segments contribute most to revenue and how to improve customer loyalty. This project demonstrates a full data pipeline: from raw data cleaning to advanced SQL querying and interactive visualization.

2. Dataset
Source: Retail Customer Transaction Data.

Size: 3,900+ rows.

Key Columns: Age, Gender, Item Purchased, Category, Purchase Amount, Subscription Status, Shipping Type, and Previous Purchases.

3. Tools & Technologies
Python (Pandas): For Data Cleaning, Handling Missing Values, and Feature Engineering.

MySQL: For deep-dive business analysis and complex data querying.

Power BI: For building an interactive dashboard and KPI tracking.

4. Project Steps
Step 1: Python - Data Cleaning & EDA
Standardized column names and handled null values to ensure data quality.

Feature Engineering: Created a new Age_group column to segment customers into categories like Young Adult, Adult, Middle-aged, and Senior.

Performed Exploratory Data Analysis (EDA) to understand basic distributions.

Step 2: SQL - Business Analysis
Imported the cleaned data into MySQL Server.

Developed queries to solve business problems, including:

Identifying the top 3 best-selling products in each category.

Calculating the total revenue contribution by different age groups.

Identifying "High-Value Non-Subscribers" (repeat buyers who haven't joined the loyalty program).

Step 3: Power BI - Interactive Dashboard
Developed a user-friendly dashboard to visualize findings.

Included KPI Cards for quick metrics (Revenue, Avg Spend).

Used Slicers for Gender and Category to allow for easy data drilling.

5. Dashboard Results & Insights
Target Audience: The Young Adult and Middle-aged segments are the highest revenue contributors.

The Subscription Opportunity: Found that 2,500+ repeat buyers are not yet members. Targeted campaigns for this group could lead to steady revenue growth.

Shipping Insights: Customers using Express Shipping spend more per order on average. Offering "Free Express Shipping" for orders over a certain amount could increase the average basket size.

6. How to Run This Project
Data: View the customer_with_age_group.csv for the cleaned dataset.

SQL: Execute the scripts in the sql_queries.sql file in your MySQL environment to see the analysis logic.

Power BI: Open the customer_behavior_dashboard.pbix file in Power BI Desktop to view and interact with the charts.

Report: Check the Project_Report.pdf for a complete summary of the business recommendations.

 Connect with Me
🔗 LinkedIn: https://www.linkedin.com/in/nayan-jain-9ba872367/
