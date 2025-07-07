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
•Morning drives the highest sales across all the stores with 54,82% followed by afternoon with 27,79% and evening being the  least with 15,38%
•Monday is our top reveue day  with 14,56%  where as Saturday and Sunday (weekends) being the least performing days.
•Coffee is are most revenue generating product category accounting a whooping 37,53%  of our total revenue.
•Monthly revenue has been increasing following a decline of 6,65% in  February showing strong operational efficiency with an increase of 21,11% in March, 45,72% in April, 92,10% in May and 103,89%
•Revenue contributions across all stores are almost equal with Hell's Kitchen leading by 33,81%, followed by Astoria with 33,25% and Lower Manhattan with 32,94%

## Recommendations 
• As our top revenue generating product category, heavily promote coffee during morning campgains when the demand is high. 
•Ensure that during peak morning hours there is appropriate staffing and products are fully stocked and readily available, to align inventory with expected sales. 
•To maximise performance on Monday offer incentive for returning  or loyal customers such as loyal customer promotions and also ensure that top staff are on duty to maintain pleasant experience for regular customers. 
•To boost sales on weekends introduce weekends only speacials. 
•Investigate February drop to identify if it was due to seasonal trends, operational disruptions or marketing gaps.

Tools and Technologies
Snowflake SQL
Microsoft Excel
Canva 
Power BI
