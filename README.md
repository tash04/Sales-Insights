# Sales Insights


## Problem Statement

This Power BI dashboard enables AtliQ hardware to gain a deeper understanding of their sales trends. It allows the business to identify key performance areas, such as revenue fluctuations, popular product categories, and regional sales variations. AtliQ can make data-driven decisions to optimize its sales strategies by visualizing these trends.

The dashboard also highlights areas for potential revenue growth, enabling the company to target specific regions or products that may be underperforming. By using this tool, AtliQ is well-positioned to increase its revenue by at least 7% in the next quarter.

Since the analysis reveals specific patterns in sales data, AtliQ can focus on improving its marketing efforts, adjusting inventory levels, and enhancing customer engagement in areas that show growth potential. This targeted approach will help the company capitalize on emerging opportunities and reduce inefficiencies in its sales process.

### Steps followed 

- Step 1 : Step 1: Loaded the sales data of AtliQ hardware into Power BI Desktop. The dataset was in a CSV file format.
- Step 2: Opened the Power Query Editor and enabled the "column distribution," "column quality," and "column profile" options under the View tab to inspect the data.
- Step 3: Adjusted the profiling to be based on the entire dataset, as the default setting only profiles 1000 rows.
- Step 4: Observed that all columns except "Sales Date" were free of errors and empty values.
- Step 5: Null values in the "Sales Date" column were excluded from the average sales calculation as they constituted less than 1% of the data.
- Step 6: Applied a custom theme in the report view for a consistent visual style.
- Step 7: Added a line chart to represent the sales trends over time, with filters (slicers) for fields such as "Product Category," "Region," and "Sales Channel" to allow dynamic data exploration.
- Step 8: Included a card visual to display the total sales revenue, filtering out null values to ensure accurate calculations.
- Step 9: Created a bar chart to display the sales distribution by product category. The "Region" field was added to the legend to show sales distribution across different regions.
- Step 10: Added a pie chart visual to represent the market share of different product categories.
- Step 11: Created calculated columns and measures using DAX to derive additional insights such as the percentage growth in sales and the total number of units sold.
- Step 12: Added text boxes to include the company’s logo and a brief summary of the insights on the dashboard.
- Step 13: Published the report to Power BI Service for broader accessibility and collaboration

# Snapshot of Dashboard (Power BI Service)

Page 1

![cr1](https://github.com/user-attachments/assets/102aff7d-ec65-4295-a103-d554affecab8)

Page 2

![cr2](https://github.com/user-attachments/assets/31fe3d2a-483e-4d42-ac55-fe4c4c748fbc)
 


# Insights

A single-page report was created in Power BI Desktop and then published to Power BI Service. The following insights were drawn from the dashboard:

### [1] Total Sales Revenue: 
The total sales revenue for the period analyzed was $12.5 million. The highest revenue was generated from the "Electronics" category, contributing 35% of the total sales.

### [2] Sales Trends Over Time:

Sales peaked in Q4 of the fiscal year, with December being the highest-grossing month.
The lowest sales were recorded in Q2, indicating a seasonal fluctuation.

### [3] Product Category Performance:

### Top Performers: 
Electronics and Home Appliances are the top-performing categories, contributing to 60% of total sales.
### Underperformers: 
The Furniture category has seen a decline in sales, with a 10% decrease compared to the previous quarter.

### [4] Regional Sales Distribution:
The North region accounts for 40% of total sales, making it the highest-performing region.
The South region has the lowest sales, suggesting a potential area for improvement or targeted marketing efforts.

### [5] Sales Channels:
Retail Stores: Retail sales account for 65% of total sales, showing the importance of brick-and-mortar stores in AtliQ's sales strategy.
### [6] Online Sales: 
Although online sales are growing, they currently contribute only 35% of total sales, indicating room for growth.

### [7] Customer Insights:
The majority of high-value sales come from returning customers, emphasizing the importance of customer retention strategies.
New customer acquisition is highest during promotional periods, particularly in Q4.

### [8] Revenue Growth Potential:
By focusing on underperforming regions and product categories, AtliQ can potentially increase revenue by at least 7% in the next quarter.
