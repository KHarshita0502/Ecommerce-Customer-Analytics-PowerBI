# :🔗  E-Commerce Customer Analytics

An end-to-end customer analytics and business intelligence project using Power BI, SQL, Python, Excel, and DAX.

1. Project Overview
   
    E-Commerce Customer Analytics is an end-to-end data analytics and business intelligence project designed to understand customer behavior, purchasing patterns, customer value, revenue performance, and churn.

     The project analyzes 30,000 orders from 8,683 unique customers across multiple countries, customer segments, products, and membership statuses.

     The objective was to transform raw transactional data into meaningful customer intelligence and actionable business insights using SQL, Python, Power Query, DAX, and Power BI.



3. Business Problem
E-commerce businesses collect large volumes of customer and transaction data, but raw transactional data does not clearly answer important business questions such as:

- Which customers are most valuable?
- Which customers are purchasing repeatedly?
- Which customers are at higher risk of churn?
- How does purchase frequency affect retention?
- Which customer segments require stronger engagement?
- How is customer churn changing over time?

Without these insights, businesses may struggle to prioritize retention efforts, improve customer engagement, and make data-driven decisions.


3. What This Project Solves
This project converts raw e-commerce transaction data into a customer analytics solution that helps the business:

- Understand customer purchasing behavior
- Identify customer value groups
- Analyze repeat-purchase behavior
- Measure customer churn
- Identify high-risk customer groups
- Compare customer segments and membership statuses
- Track churn trends over time
- Support targeted customer retention strategies



4. Project Objectives

- Analyze customer demographics and purchasing behavior
- Segment customers based on total spending
- Analyze customer purchase frequency
- Measure customer churn and retention
- Identify customer groups with higher churn risk
- Analyze revenue and order performance
- Identify important customer behavior patterns
- Provide actionable business recommendations



5. Dataset
The dataset contains:

- 30,000 orders
- 8,683 unique customers
- 36 attributes
- Customer demographics
- Order information
- Product information
- Payment details
- Shipping information
- Membership status
- Customer spending information
- Profit information
- Review ratings
- Order status and return information

The dataset covers transactions from 2023 to 2026.



6. Challenges Faced

Challenge 1 — Customer-level analysis
Several customer attributes appeared at the transaction level and could change across different orders.
To avoid misleading customer-level analysis, latest customer-level segment and membership values were derived.

Challenge 2 — Customer Lifetime Value
The raw Customer Lifetime Value field was not consistent enough for reliable customer-value segmentation.
Instead, customer total spending was calculated from transaction-level order amounts and used to create meaningful customer value groups.

Challenge 3 — Churn Definition
The dataset did not contain a predefined churn column.
A customer inactivity-based churn definition was developed using purchase behavior and a **90-day inactivity threshold**.

Challenge 4 — Purchase Frequency Analysis
Customers were grouped according to their number of orders to understand the relationship between purchase frequency and churn.

Challenge5 — Dashboard Usability
The dashboard needed to communicate multiple customer insights without becoming overloaded with unnecessary visuals.
The dashboard was therefore divided into focused analytical pages for overview, customer intelligence, and churn & retention.


7. What We Did
 
Data Preparation

- Cleaned and transformed the raw dataset
- Standardized data types and date fields
- Prepared customer-level analytical fields
- Created customer total spend
- Created customer value groups
- Prepared purchase frequency categories
- Created latest customer segment and membership fields
- Prepared data for Power BI analysis

Data Analysis
Customer behavior was analyzed across:

- Customer segments
- Countries
- Age groups
- Customer value groups
- Purchase frequency
- Membership status
- Revenue
- Churn
- Yearly churn trends


Power BI Development
An interactive three-page Power BI dashboard was developed:

Page 1 — Overview
- Customer and order KPIs
- Revenue performance
- Customer segment analysis
- Product category analysis

Page 2 — Customer Intel
- Customer age groups
- Customer value distribution
- Top countries
- Purchase frequency

Page 3 — Churn & Retention
- Churn by customer segment
- Churn by membership status
- Churn by purchase frequency
- Churn trend by year


8. Key KPIs

- Total Customers
- Total Orders
- Total Revenue
- Average Order Value
- Average Customer Spend
- Churn Rate


9. Key Findings

Customer Base
The dataset contains **8,683 unique customers** generating **30,000 orders**.

Customer Value
Low-value customers represent the largest customer value group, highlighting an opportunity to increase repeat purchases and customer spending.

Purchase Frequency
Customers with only one order have the highest churn rate, while customers with higher purchase frequency show substantially lower churn.

Churn Trend
Customer churn increased from approximately **31% in 2024 to 42% in 2026**, indicating a growing customer-retention challenge.

Purchase Frequency & Churn
Churn decreases as purchase frequency increases:

| Purchase Frequency | Churn Rate |
| 1 Order            | 76.0%      |
| 2–3 Orders         | 49.5%      |
| 4–6 Orders         | 25.5%      |
| 7+ Orders          | 13.5%      |

This indicates that repeat purchasing is strongly associated with better customer retention.


10. Business Outcomes
The project provides a data-driven view of customer behavior and retention risk.
The analysis helps the business:

- Identify customers requiring retention attention
- Prioritize one-time customers for engagement campaigns
- Encourage repeat purchases
- Identify valuable customer groups
- Monitor changes in churn over time
- Understand customer behavior across segments and membership levels
- Make more informed customer engagement decisions



11. Business Recommendations
Based on the analysis:

1.Target one-time customers with personalized offers and follow-up campaigns to encourage a second purchase.

2.Increase purchase frequency through loyalty programs, personalized recommendations, and repeat-purchase incentives.

3.Monitor high-risk customer groups using churn trends and customer-level behavior.

4.Develop targeted retention strategies for customer segments and membership groups showing higher churn.

5.Focus on customer value growth by converting low-value customers into repeat and higher-value customers.


12. Tools & Technologies

- Python
- SQL
- Microsoft Excel
- Power Query
- Power BI
- DAX


13. Skills Demonstrated

- Data Cleaning
- Data Transformation
- Exploratory Data Analysis
- Customer Analytics
- Customer Segmentation
- Customer Value Analysis
- Churn & Retention Analysis
- Data Modeling
- DAX
- Power BI Dashboard Development
- SQL
- Python
- Business Intelligence
- Data Visualization
- Business Insight Generation
