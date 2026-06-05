# Coffee  Shop Sales Analysis

## Overview
Developed an end-to-end Excel project using Coffee Shop Sales dataset, performing data cleaning, transformation, pivot tables and dashboard development.

## Problem Statement
* How have Maven Roasters sales trended over time?
* Which days of the week tend to be busiest, and why do you think that's the case?
* What times of day tend to be most popular? Does the same trend hold across all locations?
* Which products are sold most and least often? Which drive the most revenue for the business?

## Dataset
* Source: Maven Analytics- Coffee Shop Sales
* The data contains information regarding transaction_id,transaction_date,transaction_time,transaction_qty,store_id,store_location,product_id,unit_price,etc..

## Tools
* Microsoft Excel

## Methods
### Data Transformation
To preserve data integrity, the original dataset was kept unchanged and all transformations were performed on a separate worksheet.
The following data preparation steps were carried out:
*	Converted the raw dataset into an Excel Table to enable structured analysis.
*	Renamed the transaction_qty column to qty_sold for improved readability and consistency.
*	Created a total_sales column by multiplying unit_price to qty_sold .
* Extracted the Day from the transaction date to analyze sales by weekday.
*	Extracted the Hour from the transaction time to identify peak operating hours.
*	Created a Time column for easier time-based analysis.
*	Categorized transactions into Time Segments (Morning, Afternoon, Evening, and Night) to evaluate customer purchasing patterns throughout the day.
These transformations enabled deeper analysis of sales trends, customer behavior, product performance, and store-level insights.

###   Pivot Tables
After cleaning and transforming the dataset, Pivot Tables were used to summarize and analyze the data efficiently.
Key analysis included:
*	Monthly sales trend analysis.
*	Sales distribution by day of the week.
*	Quantity sold by time segment and filter is added to analyse location-wise performance across different times of the day.
*	Product category performance based on quantity sold.
*	Identification of top-selling and least-selling product categories.
*	Identifying revenue genration by product category.
Pivot Tables enabled quick aggregation of large datasets and helped uncover meaningful business insights that were further visualized through charts and dashboards.

## Key Insights
*	Revenue demonstrated strong growth throughout the first half of the year, increasing from $81.7K in January to $166.5K in June, with consistent month-over-month growth from March onward.
*	Customer activity was relatively stable across the week, with Monday, Thursday, and Friday emerging as the busiest days, while Saturday recorded the lowest transaction volume.
*	Morning hours accounted for the majority of sales (117.6K transactions), significantly outperforming afternoon, evening, and night periods, highlighting the business's dependence on breakfast and commuter traffic.
*	The morning sales pattern was consistent across all store locations, with Lower Manhattan generating the highest morning demand, while Astoria showed comparatively stronger evening activity.
*	Coffee (89,250 units) and Tea (69,737 units) were the top-selling product categories, confirming that  beverages are the primary drivers of customer purchases.
*	Bakery items (23,214 units) were the strongest non-beverage category.
*	Packaged Chocolate, Branded Merchandise, and Loose Tea were the least purchased products, indicating limited customer demand for retail and packaged goods.
*	Overall, Maven Roasters' performance is driven by weekday morning traffic and beverage sales.
  
## Data Transformation and Pivot Tables
![Cleaned Table](Coffee%20Sales%20Analysis/Pivot%20Table/Cleaned%20Table.png)
![Key Metrics](Coffee%20Sales%20Analysis/Pivot%20Table/Key%20Metrics.png)
![Monthly Sales](Coffee%20Sales%20Analysis/Pivot%20Table/Monthly%20Sales(PivotTable%201).png)
![Daily Sales Analysis](Coffee%20Sales%20Analysis/Pivot%20Table/Daily%20Quantity(PivotTable%202).png)
![Sales by Time Segment](Coffee%20Sales%20Analysis/Pivot%20Table/Sales%20by%20time%20segment(PivotTable%203).png)
![Best and Least Selling Product](Coffee%20Sales%20Analysis/Pivot%20Table/Best%20And%20Least%20Selling%20Product(PivotTable%204).png)
![Revenue by Product](Coffee%20Sales%20Analysis/Pivot%20Table/Revenue%20by%20Product%20Category(PivotTable%205).png)

## Dashboard
![Dasboard](Coffee%20Sales%20Analysis/Dashboard/Image.png)

## Recommendations
 Based on the analysis, the following recommendations can help Maven Roasters improve sales and operational efficiency:
*	Focus on maximizing morning sales, as this period generates the highest customer traffic across all locations.
* Ensure adequate staffing and inventory availability during peak morning hours.
*	Introduce afternoon and evening promotions such as combo deals, happy-hour discounts, or loyalty rewards to increase traffic during off-peak periods.
*	Continue prioritizing Coffee and Tea offerings, as these categories drive the majority of sales and customer demand.
*	Leverage the popularity of Bakery products by creating bundled meal deals with beverages to increase average transaction value.

## Author
**ANCHAL CHILWAL**

## Contact Info
* LinkedIn:(https://linkedin.com/in/anchal-chilwal-30b359408)
* GitHub:(https://github.com/AnchalChilwal)


