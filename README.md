# Adventure Work Bike 

## Project Overview
You’ve just been hired as a Business Intelligence Analyst by AdventureWorks*, a global 
manufacturing company that produces cycling equipment and accessories
The management team needs a way to track KPIs (sales, revenue, profit, returns), compare 
regional performance, analyze product-level trends, and identify high-value customers.

## Objective
Use Power BI Desktop to: 
• Connect and transform the raw data
• Build a relational data model
• Create calculated columns and measures with DAX
• Design an interactive dashboard to visualize the data

## Data Sources
The project uses the AdventureWorks dataset, provided as an Excel workbook containing the following tables:
Fact Table: Sales data
Dimension Tables: Product, Customer, Sales Order, Sales Territory, Reseller, Calendar Date

## ETL Process
1. Extract: Data was extracted from an Excel workbook using Power BI’s data connectors.
2. Transform: Data cleaning was performed using Power Query Editor, ensuring appropriate data types and relationships between tables.
3. Load: Transformed data was loaded into the Power BI data model for reporting.

## Data Model
I implemented a star schema with the Sales table as the central fact table, connected to six dimension tables (Product, Customer, Sales Order, etc.), creating a robust data model for analysis.


## DAX Functions
Key metrics were calculated using DAX functions, including:
`SUMX` for aggregating row-based calculations.
`CALCULATE` to create custom filters.
`DateAdd` and `DATESINPERIOD` for time-based analysis like 90-day rolling profits.

## Visualizations
Four dashboards were created:
1. Sales Overview: KPIs including Total Sales, Profit, and Orders.
2. Customer Insights: Visualizations of sales by customer demographics.
3. Product Performance: Sales distribution across products and time.
4. Geographical Sales: A map showcasing sales distribution by region.

   ![image](https://github.com/user-attachments/assets/911821b1-80d3-48f6-9e8f-51368a9115e6)
   ![image](https://github.com/user-attachments/assets/8f32066c-6959-4c9d-8deb-d1db7006e574)



## Future Improvements
1. Adding real-time data analysis with enhanced Snowflake integration.
2. Expanding the report to include more advanced sales forecasting and customer segmentation.

