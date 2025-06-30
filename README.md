# Coffee-shop-sales-project
The objective of this project was to analyse sales data from a coffee shop to find patterns and key insights to help the new appointed CEO to make data informed decisions that can enhance revenue and the overall performance.

## Data Source 
The original data was collected from Point of Sale (POS) system. Exported to Excel and transformed for analysis.The final dataset was processed and modelled using SQL Snowflake.

## Data Pipeline
**Extract** - the Excel file was exported from POS system 
**Transform** - fixed format in Excel(the dates were not in the correct format)
**Load** - the CSV file was loaded into snowflake for SQL processing.

## Data Processing 
•Performed in Snowflake
•Cleaned the unit price into the correct format 
•Created time buckets
•Added a new column 'total amount=unit_price× transaction_quantity'
•Created a new colmn purchase_date,month_name and day_name using the transaction_date column 
•Aggregatimg sales, quantity sold and revenue by product_category,store_location, time, date

## Data Analysis and Visualisation 
•Excel pivot tables and Charts 
•Monthly revenue trends
•Revenue by product category 
•Peak sales hours
•Week days sales trends
•Store performance level

## Key insights
•Morning drives the highest sales across all the stores
•Monday is our top reveue day with weekends days such as Saturday and Sunday being the least performing days.
•The product are divided into three sub categories the core revenue drivers, balanced performers and premium products.

## Recommendations 
•Focus operations and promotions on 'mornimg peak hours).
•Promote core drivers lile coffee and bakery Combos 
•Realign weekend strategy with clearance 
•Upsell premium products through bundles and loyalty program.

Tools and Technologies
Snowflake SQL
Microsoft Excel
Canva 
