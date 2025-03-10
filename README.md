# Sales-analysis
Detailed sales analysis by customer, product, manufacturer, geography, segment, and category. 

- Measurement of KPIs such as total sales, daily, and monthly.
- Identification of optimization opportunities and growth strategies based on the analyzed data.

Case: Requirements Gathering

Topics: Sales Analysis
Explained by: Customer, product, manufacturer, geography, segment, category, time

What will be measured:
  - Total sales (quantity and value in R$)
  - Daily variations (quantity and value in R$)
  - Monthly variations (quantity and value in R$)
  - Yearly variations (quantity and value in R$)
  - Average Ticket (quantity and value in R$)
  - YTD (Year-To-Date) accumulation (quantity and value in R$)
  - MTD (Month-To-Date) accumulation (quantity and value in R$)
  - YTD accumulated variation (quantity and value in R$)
  - MTD accumulated variation (quantity and value in R$)


![image](https://github.com/user-attachments/assets/337bd02d-6814-47d2-a05e-3af5a4d04353)

Objective: Build a Data Lake with a Medallion Architecture

- Landing Zone: Where the data is stored in its raw form, without any additional processing.
- Bronze: Where the data is stored in its raw form, without any additional processing.
- Silver: Where the data is pre-processed for cleaning and deduplication.
- Gold: Where the data is transformed into a more readable form for reporting and analysis and stored for large-scale analysis and generating value for the business.
