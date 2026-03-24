# Bright-Coffee-Shop

Introduction

You have been provided with a dataset titled “Bright Coffee Shop Sales” which captures daily transactional information from a coffee shop. The business has recently appointed a new CEO whose mission is to grow the company’s revenue and improve product performance. Your role, as a Junior Data Analyst, is to extract actionable insights from historical data and prepare a presentation to assist the CEO in decision-making.

Objective
Use your analytics, SQL, and data visualization skills to help Bright Coffee Shop understand:

- Which products generate the most revenue
-What time of day the store performs best
-Sales trends across products and time intervals
-Recommendations for improving sales performance

Tasks
Tasks 1: Planning & Architecture (Miro)

-Design a Data Flow & Architecture Diagram that outlines
-Where the data comes from (source)
-How it is processed (ETL pipeline)
-Where it is stored (Databricks)
-How it is analyzed and presented

2.List the Key Insights that the team should deliver, such as

-Sales by product category and time intervals
-High-performing and low-performing products
-Total revenue calculations

3.Outline the calculations to be performed

-Total Amount = unit_price * transaction_qty
-Grouping by 30-minute time intervals
-Total units sold by product type or detail

You can add on the above, this is just to give you an idea of what is expected from the Miro planning.

Tasks 2: Data Processing in Databricks

-Convert the provided Excel data to CSV
-Load the CSV into Databricks
-Perform data transformations:

    *Create a new column: “transaction time_bucket” to group transactions into 30-minute intervals (Or it can be 3 hour intervals)
    *Cast “unit_price” properly (some entries use commas, e.g.,to 3.1 should be converted)
    *Compute “total amount = unit_price * transaction_qty”
    *Use SQL to group by product types, time buckets, etc.

You can add on the above, this is just to give you an idea of what is expected from the Data Processing.

Tasks 3: Data Analysis in Excel
After processing the data in Databricks:
-Export the processed table to Microsoft Excel or your visualization tool
-Create dashboards or pivot tables showing:

    *Total revenue per product type
    *Peak time intervals for sales
    *Quantity of items sold by product category
    *Best-selling product types or details
    *Use charts and graphs to make the story visually appealing
    
Tasks 4: Presentation to the CEO
-Overview of your approach – Create a separate document for your Methodology
-Key insights from your analysis (backed by visuals) – Create a separate document for your Presentation
-Recommendations:

    *Marketing campaigns during slow time slots
    *Stock more of the best-selling items
    *Promote underperforming products
- Next Steps:
- 
    *Automate daily sales reporting
    *Track sales performance across multiple locations in the future
    *Implement loyalty programs based on peak customer time slots
