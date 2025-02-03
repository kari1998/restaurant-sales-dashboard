# Local Restaurant Sales Dashboard

## Project Overview

This project analyzes restaurant sales data to identify key trends, top-performing items, and opportunities for improvement. The analysis covers sales trends over time, top-selling items and order type insights ( delivery income & dine ins). The results are visualized in a series of charts displayed in this file, while the complete data, calculations, and detailed analysis can be found in the accompanying Excel workbook (`analysis/Sales Data for Local Restaurant_Oct-Dec_2024 `).

## Business Problem

Understanding sales trends is crucial for the restaurant to make informed decisions about menu planning, inventory management, staffing, and marketing strategies. Identifying top-selling items allows the restaurant to focus on its strengths and optimize its menu offerings. Analyzing order types helps the restaurant understand customer preferences and potentially tailor its services. Tracking delivery income provides insights into the growing segment of the business. This analysis aims to provide actionable recommendations to improve the restaurant's overall performance and profitability.

## Data Description

The dataset used in this analysis contains sales data for the restaurant over a three-month period (October - December). The data includes information on the date of each transaction, the items sold, the quantity sold, the revenue generated and the order type (dine-in or delivery). The dataset contains [7058] records. *Note: This dataset is a sample dataset created for demonstration purposes.*

The key variables analyzed in this project include: Date, Item Name, Quantity, Revenue and Order Type.

## Data and Analysis

The raw sales data was cleaned and preprocessed in Google Sheets to ensure data consistency and handle any missing values. Pivot tables were used to aggregate sales data by month, item category and order type. The charts presented in this file were created in Google Sheets and saved as PNG images for easy viewing. The complete data and detailed calculations can be found in the `analysis/Sales Data for Local Restaurant_Oct-Dec_2024 ` workbook.

## Analysis and Visualizations

The following sections present the key findings of the analysis, organized by the questions they address. The charts are displayed as images for easy viewing, while the complete data, calculations, and detailed analysis can be found in the accompanying Excel workbook (`analysis/restaurant_sales_analysis.xlsx`).

### Sales Trends

#### What are the total sales and quantities sold each month?

**Approach:** A combined line chart was used to visualize monthly sales and quantities, allowing for easy comparison of trends. This chart was created in Google Sheets and saved as a PNG image. The underlying data and calculations can be found in the Excel workbook in the `analysis/` folder.

**Visualization:**

![Sales_&_Quantity_Sold_Per_Item_In_October](images/Sales%20_In_October.png)
![Sales_&_Quantity_Sold_Per_Item_In_October](images/Sales%20&%20Quantity%20Sold%20Per%20Item%20In%20November.png)
![Sales_&_Quantity_Sold_Per_Item_In_October](images/Sales%20&%20Quantity%20Sold%20Per%20Item%20In%20December.png)

**Interpretation & Insights:** (Your interpretation of the chart, e.g., upward trend, peak in December, November dip)

**Actionable Recommendations:** (Your recommendations based on the insights)

#### What are the daily sales patterns?

**Approach:** A line chart was used to visualize daily sales trends, highlighting any patterns or fluctuations. This chart was created in Microsoft Excel (or Google Sheets) and saved as a PNG image. The underlying data and calculations can be found in the Excel workbook in the `analysis/` folder.

**Visualization:**

![daily_sales_trend.png](images/daily_sales_trend.png)

**Interpretation & Insights:** (Your interpretation of the chart, e.g., weekly patterns, weekend spikes)

**Actionable Recommendations:** (Your recommendations based on the insights)

### Top Performers

#### Which items are the top sellers by quantity and revenue?

**Approach:** A combined bar chart was used to compare the top-selling items by both quantity and revenue. This chart was created in Microsoft Excel (or Google Sheets) and saved as a PNG image. The underlying data and calculations can be found in the Excel workbook in the `analysis/` folder.

**Visualization:**

![top_sellers.png](images/top_sellers.png)

**Interpretation & Insights:** (Your interpretation of the chart, e.g., top-selling items)

**Actionable Recommendations:** (Your recommendations based on the insights)

#### Which item categories contribute the most to total sales?

**Approach:** A pie chart was used to visualize the percentage contribution of each item category to total sales. This chart was created in Microsoft Excel (or Google Sheets) and saved as a PNG image. The underlying data and calculations can be found in the Excel workbook in the `analysis/` folder.

**Visualization:**

![category_contribution.png](images/category_contribution.png)

**Interpretation & Insights:** (Your interpretation of the chart, e.g., category contributions)

**Actionable Recommendations:** (Your recommendations based on the insights)

### Order and Payment Insights

#### How do order types (e.g., dine-in, takeout, delivery) compare in terms of revenue?

**Approach:** A bar chart was used to compare the revenue generated by each order type. This chart was created in Microsoft Excel (or Google Sheets) and saved as a PNG image. The underlying data and calculations can be found in the Excel workbook in the `analysis/` folder.

**Visualization:**

![order_type_revenue.png](images/order_type_revenue.png)

**Interpretation & Insights:** (Your interpretation of the chart, e.g., comparison of order types)

**Actionable Recommendations:** (Your recommendations based on the insights)

### Delivery Income Analysis

#### What is the trend of income generated by deliveries over time?

**Approach:** A line chart with a trendline was used to visualize the trend of delivery income over time. This chart was created in Microsoft Excel (or Google Sheets) and saved as a PNG image. The underlying data and calculations can be found in the Excel workbook in the `analysis/` folder.

**Visualization:**

![delivery_income.png](images/delivery_income.png)

**Interpretation & Insights:** (Your interpretation of the chart, including observations about the trendline)

**Actionable Recommendations:** (Your recommendations based on the insights, e.g., "Given the upward trend, the restaurant should consider investing in additional delivery resources...")

## Key Findings

(Summarize the *most important* insights and their implications for the restaurant)

## Tools Used

*   Google Sheets
    *   Data Cleaning and Transformation
    *   Pivot Table Analysis
    *   Interactive Dashboard Creation (using Slicers)
    *   Charting and Visualization

## Next Steps

*   **Data Enrichment and Expansion:** (Ideas for incorporating external data, customer demographics, etc.)
*   **Advanced Analytical Techniques:** (Suggestions for regression analysis, time series analysis, etc.)
*   **Operational Improvements and Recommendations:** (Ideas for inventory management, staffing optimization, menu engineering, etc.)
*   **Specific to Your Charts:** (Relate next steps to specific insights from your charts, e.g., "Given the strong performance of the 'Burgers' category, future analysis could focus on optimizing burger recipes and pricing strategies.")