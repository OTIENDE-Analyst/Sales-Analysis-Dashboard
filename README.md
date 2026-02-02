# Sales-Analysis-Dashboard
This project showcases an end to end sales data analysis workflow using Microsoft Excel. From data cleaning and transformation to analysis and visualizations. The goal is to examine the sales data inorder to discover patterns and draw insights that support data-driven decision making through KPIs and interactive visuals.

# Workbook Structure
1.Data: Raw collected data.

2.Brief: A brief on what to do with the data

3.Staging Table: used for the data cleaning and transformation

4.Region_Hierachy_Pivottable: 

5.Pivot table of ProductCategory and Pricebands

6.Cohort Analysis:

7.ABC Analysis: of SKUs based on Revenue contribution

8.Salesperson productivity metrics

9.Channelmix and Cannibalization

10. Sevice level proxy: % of orders meeting 7 day target
    
11.Price compliance: share of orders with discountpct>20%

12.WhatIf control pannel with sliders

13.Revenue by Month PivotTable and chart

14.Profit by Region and Channel PivotTable and chart

15.Top 10 SKUs by Revenue PivotTable and chart

16.Discount Outliers PivotTable and chart

17.Dashboard: interactive dashboard with slicers, KPIsand charts

# Tools Used
Microsoft Excel

Pivot Tables and Charts

Slicers and Filters

# Data Cleaning and Assumptions Done
Duplicates removed

Data types fixed appropriately

Blank City and Salesperson cells replaced with "Unknown"

Blank Channel cells replaced with "Not provided"

Negative Unit Prices flagged (using Conditional formating) and set equal to Unit cost.

OrderDates earlier than RequiredDate flagged and standardized to 7 days before RequiredDate.

# Dashboard Highlights
KPIs: Total Revenue, Gross Profit, Average Margin, Average OrderValue, On-Time %

Reveunue trends by Month

Top 10 SKUs by Revenue

Profit by Region and Channel

Discount outliers visualization

# Dashboard Preview
![Sales_dashboard preview](https://github.com/user-attachments/assets/b222f6af-a9cc-4d7d-9e83-e4d24561edb0)

# Key Insights
Months May to August recorded the highest Revenue, contributing about 45% of the Total Gross Revenue. Revenue shows mid year peak.

In Africa, SKU LAP-8910 was the top performer contributing to 16% of Africa's total Revenue.

In America, Direct + Online channels accounted for approximately 60% of total Revenue.

For Asia, the Direct Channel generated 26% of the Gross profit, making it the most profitable cahannel in the region.

In Europe the strongest Revenue month was April, accounting for 15% of the Total Gross Revenue

Direct and Online Channels consistently outperform others, indicating areas of strategic investment.

