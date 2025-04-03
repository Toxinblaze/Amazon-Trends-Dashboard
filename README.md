# Amazon-Sales-Data Analysis (Interactive Dashboard creation using Power BI)
## Project Objective 
To create a report which analyze and optimize sales performance, profitability, and market reach by leveraging data on products, channels, geographies, and seasonal trends from 2010 to 2017

## Dataset used
- <a href="https://github.com/Toxinblaze/Amazon-Trends-Dashboard/blob/main/AmazonSalesData.xlsx">Dataset</a>

## Data Visualization & Dashboard Creation (KPIs)
- I created a Power BI report with the following:
- Sales Performance Dashboard
- A Card visualization displaying Total Sales.
- A Bar Chart showing Sales by Product.
- A Pie Chart displaying Sales by channel.
- A Line Chart to visualize Sales Trend over Time (Year, Quarter, Month).
- A Map showing Sales by Country.
- A Table listing the Top 5 Products by Sales & Profit Margin.

## Interactivity & Insights
- I added a slicer for filtering data by Year and Country.
- Also added tooltips showing additional details when hovering over data points.

-	Dashboard Interaction <a href="https://github.com/Toxinblaze/Amazon-Trends-Dashboard/blob/main/Amazon%20Sales%20Overview1.png">View Dashboard</a>

## Process 
# Power Query - Data Cleaning & Transformation
- Remove any unnecessary columns.
- Check for and handle missing values.
- Format date fields properly.
- Create a Calendar Table using DAX

# Created New Columns in Power Query
- Sales Column
- Revenue Column
- Profit Column

# DAX Measures & Calculations
- Total Sales
- Total Profit
- Total Cost
- Average Profit per Sale
- Top-Selling Product
- Profit Margin (%)

## Dashboard

![Amazon Sales Overview1](https://github.com/user-attachments/assets/b819e4f0-3c70-4c50-b2e5-60621ad365ad)

## Project Insights 
# Profitability & Sales Growth
-	High Profitability: With a total profit of $44.14M from $137.32M in sales, Amazon is maintaining a healthy profit margin.
-	Low Cost Relative to Revenue: The total cost is $19.1K, which is significantly low compared to revenue, indicating cost efficiency.
# Top-Performing Products & Profit Margins
-	Cosmetics ($37M) and Office Supplies ($31M) are the highest revenue generating products.
-	Clothes have the highest profit margin (67.16%), followed by Baby Food (37.53%) and Cosmetics (39.75%).
-	Office Supplies have a lower profit margin (19.37%), despite high sales.
# Sales Channel Distribution
-	Offline Sales (57.58%) outperform Online Sales (42.42%), showing that physical stores or third-party offline distributors play a key role.
-	Potential Insight: Amazon may want to strengthen its online sales strategy to increase digital revenue.
# Geographical Sales Distribution
-	Sales are spread across multiple countries, with a high concentration in Europe and North America.
-	There may be an opportunity for expansion into emerging markets where presence is currently lower.
# Seasonal Sales Trends
-	February ($25M) and November ($21M) saw peak sales, likely due to promotions, holidays, or seasonal demand.
-	March ($2M) and August ($1M) had the lowest sales, suggesting potential areas for marketing and sales improvements during these months.

