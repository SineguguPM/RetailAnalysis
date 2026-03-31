# RetailAnalysis
This project analyses retail sales transactions to uncover customer behaviour, revenue trends, and shopping patterns. The insights are visualized in an interactive Power BI dashboard.

The goal of this project is to:
•	Identify revenue drivers across product categories.
•	Understand customer demographics and spending behaviour.
•	Evaluate payment methods and shopping mall performance.

Data Description
•	Source: The dataset was obtained from a past academic project. It contains transactional retail data including customer demographics, product categories, payment methods, and sales amounts. While the exact source is unknown, the dataset is suitable for demonstrating SQL queries, data cleaning, and visualization techniques.

•	Table: RetailAnalysisDataset
•	Rows: 99 460
•	Columns:
o	invoice_no – unique transaction ID
o	customer_id – customer identifier
o	gender, age, age_category – demographics
o	category – product category
o	quantity, price, total_spent – transaction details
o	payment_method – cash, card, etc.
o	invoice_date – transaction date
o	shopping_mall – location of purchase

Data Preparation
•	Cleaned currency formats ($1 500,40 to 1500.40).
•	Removed duplicates and invalid entries.
•	Created derived fields (age_category, total_spent).
•	Standardized date formats for time-series analysis.

Analysis & Metrics
•	Total Revenue - The overall revenue generated across all transactions. This provides a clear view of the business’s scale and performance.
•	Revenue by Category – Breakdown of sales by product category. This shows which categories are the strongest revenue drivers and highlights opportunities for growth or improvement.
•	Top 5 customers - Ranking of customers by total spending. Identifying the highest value customers helps demonstrate loyalty patterns and potential for targeted marketing.
•	Customer Demographics – Analysis of spending by age group and gender. This reveals which demographic segments contribute most to revenue and can guide customer engagement strategies.
•	Most Popular Payment Method – Distribution of transactions by payment type. This insight highlights customer preferences and informs operational decisions (e.g., which payment systems to prioritize).
•	Revenue per Shopping Mall – Comparison of revenue across different shopping mall locations. This shows geographic performance and helps identify top performing sites versus underperforming ones.
•	Monthly Revenue – Time series analysis of revenue trends by month. This highlights seasonal patterns, peak shopping periods, and potential slowdowns, which are critical for forecasting and resource planning.

Key Insights
•	Shoes and technology are the top revenue drivers.
•	Seniors (aged 51+ years) contribute the highest spending.
•	Cash dominates as the preferred payment method.
•	Mall of Istanbul outperforms other malls.

9. Conclusion & Next Steps
This analysis highlights customer behaviour and revenue trends in retail sales. Future work could include:
•	Predictive modelling for sales forecasting.
•	Customer segmentation for targeted marketing.
•	Integration with external datasets (e.g., economic indicators).
