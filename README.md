# Performance Report Dashboard

This project is a Power BI dashboard that visualizes key performance indicators (KPIs) related to the financial performance of a company.
The dashboard provides an interactive and comprehensive view of year-to-date (YTD) and prior year-to-date (PYTD) performance metrics, segmented by various dimensions such as country, product type, and profitability. Users can switch between different metrics including Gross Profit, Quantity, and Sales.

## Features

- **Interactive Filters**: Users can filter the data by metric categories (Gross Profit, Quantity, Sales) and select the year.
- **Key Performance Indicators (KPIs)**: 
  - **YTD Metric**: Displays the total value of the selected metric (Gross Profit, Quantity, or Sales) year-to-date.
  - **PYTD Metric**: Shows the total value of the selected metric for the same period in the previous year.
  - **YTD vs PYTD Difference**: Highlights the difference in the selected metric between the current year and the previous year.
  - **Gross Profit Percentage (GP%)**: Indicates the gross profit margin as a percentage.

## Visualizations

![image](https://github.com/user-attachments/assets/32ff4b31-9337-4bcc-afad-da70c9c099c6)


1. **Bottom 10 by YTD vs PYTD | Country**:
   - A treemap visualization showing the bottom 10 countries based on the YTD vs PYTD difference for the selected metric. This helps identify underperforming regions.


2. **YTD vs PYTD**:
   - A waterfall chart that displays the monthly comparison between YTD and PYTD for the selected metric. It visually represents increases and decreases over the months.


3. **YTD & PYTD | Month**:
   - A clustered column chart that compares the monthly values for different product types (Indoor, Landscape, Outdoor) against the prior year’s data for the selected metric.


4. **Account Profitability Segmentation | By GP% and Gross Profit**:
   - A scatter plot that segments accounts based on their Value YTD and GP%.
