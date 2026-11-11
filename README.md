# Sales Data Analysis Using Power BI

This project focuses on cleaning, transforming, and analyzing a sales dataset using Microsoft Power BI to derive meaningful insights into regional order distribution, product performance, and profit trends.

### Project Tasks & Implementation

**1. Data Cleaning and Transformation**
- Imported the CSV dataset into Power BI using Power Query Editor.
- Identified and handled missing values.
- Removed duplicate records to maintain data accuracy.
- Standardized the `OrderDate` column into a consistent date format.
- Loaded the cleaned dataset into the Power BI data model.

**2. Data Visualization and Analysis**
- Created a **Pie Chart** to analyze order distribution across different regions.
- Developed a **Column Chart** to identify the top 5 trending products based on order frequency.
- Designed a **Line Chart** to visualize profit trends over time.

**3. DAX Calculations**
- Created a calculated table, `EastRegionOrders`, to display orders exclusively from the East region.
- Added a calculated column, `ProfitCostDifference`, to calculate the difference between Profit and Cost.
- Created a measure, `TotalProfit`, to calculate the overall profit earned.

### Tools & Technologies
- Microsoft Power BI
- Power Query Editor
- DAX (Data Analysis Expressions)
