# Performance Report & Analysis - PowerBI
## --- Project Documentation ---
A dynamic PowerBI dashboard analyzing sales performance and profitability for PlantCo.

## Table of Contents
a. Problem Statement

b. Project Overview & Tools

c. Importing Process

d. Data Modeling & DAX Measures

e. Visualizations

f. Key Insights

g. Strategic Recommendations

## a. Problem Statement
PlantCo needs a comprehensive view of their sales performance, comparing current year-to-date metrics against prior year, with the ability to analyze trends by product, country, and account profitability.

## b. Project Overview (5Ws) & Tools
5Ws:
- WHAT: An interactive PowerBI dashboard to analyze PlantCo's sales performance and profitability
- WHY: To identify growth opportunities, underperforming areas, and segment accounts by profitability
- HOW: Using PowerBI for ETL, data modeling, and visualization
- WHERE: Data sourced from Excel files; visualized in PowerBI
- WHO: For PlantCo management to make data-driven decisions on sales strategies

Tools used:
- Excel (source data)
- PowerBI Desktop (ETL, modeling, visualization)
- DAX (for measures and calculated columns)

## c. Importing Process
1. Imported Excel files into PowerBI
2. Performed minor data cleansing in Power Query:
   - Renamed tables (e.g., "Plant Fact" to "Fact Sales")
   - Adjusted column names and data types
   - Removed duplicates from dimension tables
3. Created a date dimension table using DAX

## d. Data Modeling & DAX Measures
1. Created relationships between fact and dimension tables
2. Developed key measures:
   - Base measures (Sales, Quantity, Gross Profit)
   - Year-to-Date (YTD) measures
   - Prior Year-to-Date (PYTD) measures
   - YTD vs PYTD comparison measures
   - Gross Profit Percentage
3. Implemented switch measures for dynamic metric selection

## e. Visualizations
1. Header metrics using new card visuals with conditional formatting
2. Treemap showing bottom 10 countries by YTD vs PYTD performance
3. Waterfall chart displaying YTD vs PYTD breakdown by month and product
4. Line and stacked column chart comparing YTD and PYTD metrics over time
5. Scatter plot for account profitability segmentation
6. Slicers for year and metric selection

## f. Key Insights
1. Year-over-Year Performance:
- Significant decline in March and April 2024 compared to prior year
- February 2024 showed exceptional performance, exceeding prior year metrics

2. Geographic Analysis:
- Canada emerged as a major contributor to recent declines, particularly in April
- Bottom 10 countries by YTD vs PYTD performance include Canada, Colombia, Croatia, and Germany

3. Product Category Trends:
- Landscape products in Canada showed notable underperformance
- Certain product types (e.g., outdoor plants) experienced more significant declines than others

4. Account Profitability Segmentation:
- Identified a cluster of accounts with above-average Gross Profit Percentage (GP%) but low sales volume
- Some accounts demonstrated high sales volume but lower than average GP%

5. Seasonal Patterns:
- February consistently strong across years, indicating potential seasonal opportunity
- Varying performance across different quarters, suggesting need for tailored quarterly strategies
  
## g. Strategic Recommendations
1. Targeted Geographical Strategies:
- Conduct in-depth market analysis for Canada to identify root causes of recent performance decline
- Develop country-specific action plans for bottom 10 performing countries, considering local market conditions and competition

2. Product Portfolio Optimization:
- Review and potentially restructure the landscape products offering in Canada
- Investigate successful product lines and consider expanding their distribution to underperforming regions

3. Account Management and Sales Strategies:
- Implement a focused sales initiative for accounts with high GP% but low sales volume to increase their order sizes
- Develop retention strategies for high-volume accounts, with a focus on improving their GP%
- Create an account scoring system based on both volume and profitability to prioritize sales efforts

4. Seasonal Preparedness:
- Capitalize on February's consistent strong performance by planning targeted marketing campaigns and ensuring optimal inventory levels
- Develop off-season strategies to mitigate performance dips in slower months

5. Product Hierarchy Analysis:
- Conduct a detailed analysis of performance across different levels of the product hierarchy
- Consider restructuring product groupings or focusing marketing efforts on high-performing categories

6. Performance Monitoring and Forecasting:
- Implement regular (weekly or monthly) performance reviews using the dashboard to quickly identify and respond to trends
- Develop a forecasting model based on historical data to set realistic targets and identify potential issues in advance

7. Customer Segmentation Strategy:
- Use the account profitability scatter plot to create distinct customer segments
- Develop tailored marketing and sales approaches for each segment to optimize overall portfolio performance

## Conclusion
By implementing these recommendations and continuously monitoring performance through the PowerBI dashboard, PlantCo can make data-driven decisions to improve sales, optimize profitability, and drive sustainable growth across its diverse product portfolio and geographical markets.
