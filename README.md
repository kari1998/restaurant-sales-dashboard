# Local Restaurant Sales Dashboard

## Project Overview

This project analyzes restaurant sales data from October to December to identify key trends, top-performing items, and opportunities for improvement.  The analysis covers sales trends over time, top-selling items, order type insights (dine-in and delivery), and delivery income trends.  The results are visualized below, with full data, calculations, and detailed analysis in the accompanying Excel workbook (`analysis/Sales Data for Local Restaurant_Oct-Dec_2024`).

## Business Problem

Understanding sales trends is crucial for informed decisions regarding menu planning, inventory, staffing, and marketing. Identifying top sellers allows focus on strengths and menu optimization. Analyzing order types reveals customer preferences. Tracking delivery income provides insights into this growing segment. This analysis aims to provide actionable recommendations to improve performance and profitability.

## Data Description

The dataset contains sales data from October to December, including transaction date, items sold, quantity, revenue, and order type (dine-in/delivery).  It contains 7058 records. *Note: This is a sample dataset for demonstration.* Key variables include Date, Item Name, Quantity, Revenue, and Order Type.

## Data and Analysis

Raw data was cleaned and preprocessed in Google Sheets. Pivot tables aggregated data by month, item, and order type. Charts were created in Google Sheets and saved as PNGs. The complete data and calculations are in the `analysis/Sales Data for Local Restaurant_Oct-Dec_2024` workbook.

## Analysis and Visualizations

### Sales Trends

#### What are the total sales and quantities sold each month?


**Approach:** A combined line and bar chart visualizes total monthly sales and total monthly quantities.

**Visualization:** 

![Total_Sales_&_Quantity_Sold_Per_Month](images/Total%20Sales%20&%20Quantity%20Sold%20per%20Month.png) 

**Interpretation & Insights:**

**Top-Selling, Low-Priced Products:**

* The increase in quantity sold in November and December can largely be attributed to these low-cost, high-demand products (tea and chapati).
* The mismatch between revenue and quantity growth is likely due to the heavy sales volume of these cheaper items, which has a limited effect on overall revenue growth.

**Price Sensitivity:** Since the top-selling items are low-cost, customers may be price-sensitive, which limits the potential for increasing average sales value unless higher-priced items are marketed more effectively.


**Actionable Recommendations:**

* Consider introducing promotions for higher-priced items to increase the average revenue per sale. Marketing campaigns should focus on upselling or bundling premium products with popular low-cost item
* Analyze whether the pricing of tea and chapati can be slightly adjusted without significantly impacting sales volumes. Even minor price increases on top-selling items could have a meaningful effect on total revenue.
* Encourage customers to buy complementary higher-margin products with tea and chapati. For example, pairing tea with baked goods or promoting meal combos could increase the average ticket size.


#### What are the daily sales patterns?

**Approach:** A line chart visualizes daily sales trends, highlighting patterns and fluctuations.

**Visualization:**

![daily_sales_trend.png](images/Daily%20Sales%20Trend%20in%20October.png)

![daily_sales_trend.png](images/Daily%20Sales%20Trend%20in%20November.png)


![daily_sales_trend.png](images/Daily%20Sales%20Trend%20in%20December.png)

**Interpretation & Insights:** 
* **Sales Fluctuations:** Sales varied daily, with noticeable peaks and dips in each month. Some days consistently recorded higher sales, indicating potential factors such as promotions, customer behavior, or external influences.
* **Recurring Weekly Pattern:** After further analysis a noticeable trend emerged where sales would typically rise on Thursdays or Fridays, peak on Sundays, and then drop on Tuesdays. This pattern suggests increased customer activity towards the weekend, possibly due to higher foot traffic, or weekend dining behavior.

**Month-to-Month Comparison:** 
* **October:** Sales showed a gradual increase, with a significant peak towards the end of the month.
* **November:** Sales remained relatively stable, with occasional spikes, particularly in the last week.
* **December:** Sales started strong but showed more fluctuations, possibly due to seasonal demand changes.



**Actionable Recommendations:** 

* **Staffing:** Adjust weekly staffing levels to align with the observed sales patterns. Increase staff on Thursdays, Fridays, and Sundays to manage peak demand. Evaluate staffing levels on Tuesdays (and potentially Wednesdays) for potential reductions, while ensuring adequate service.
* **Targeted Promotions:** Implement day-specific promotions to optimize sales. Consider:
    * **Tuesday Specials:** Offer discounts or special menus on Tuesdays to attract more customers on the traditionally slower day.
    * **Weekend Deals:** Offer attractive brunch, lunch, or dinner deals on weekends to capitalize on peak demand.
    * **Weekday Value Menus:**  Introduce value-focused menus for weekday lunches to attract a consistent lunch crowd.
    * **External Factors:**  Explore correlations between daily sales and external factors like weather, local events, or competitor activities to understand fluctuations and potentially predict trends.


### Top Performers

#### Which items are the top sellers by quantity and revenue?

**Approach:** Combined charts visualize sales and quantities for each item across the three months.

**Visualization (October):**

![Sales & Quantity Sold Per Item In October](images/Sales%20_In_October.png)

**Interpretation & Insights (October):** 
Chapati and Tea dominate in sales and quantity, followed by Uji and Fries.

**Actionable Recommendations (October):** 
Maintain quality and availability of Chapati and Tea. Investigate strategies to ensure consistent availability of Uji and Fries.

**Visualization (November):**

![Sales & Quantity Sold Per Item In November](images/Sales%20&%20Quantity%20Sold%20Per%20Item%20In%20November.png)

**Interpretation & Insights (November):** 
Chapati and Tea still dominate in sales and quantity, followed by Uji and Pilau, there is a noticeable drop with fries.

**Actionable Recommendations (October):** 
* **Chapati and Tea:** Maintain the consistent quality and availability of Chapati and Tea. These are your top performers, and ensuring their continued popularity is crucial for sustained revenue.  Consider strategies to further promote these items, perhaps through bundled deals or loyalty programs.

* **Uji:** Investigate strategies to ensure the consistent availability of Uji. Consistent availability is key to capturing this market segment.  Analyze the demand patterns for Uji – **are there specific times of day or days of the week when demand is highest?** Adjust production accordingly.

* **Fries:** Investigate the reasons for the drop in sales of Fries.  Several factors could be contributing:

1) Is the price of Fries competitive? Conduct a comparative analysis of pricing at other local restaurants.
2) Are Fries consistently available throughout the day? Issues with the fryer or staffing could lead to stockouts.

* **Pilau:** Explore strategies to capitalize on the potential displayed by Pilau to increase its revenue.

1) Ensure the Pilau is presented attractively on the menu and when served to customers.
2) Evaluate the portion size of Pilau. A slightly larger portion might justify a higher price and increase customer satisfaction.
3) Suggest complementary items that pair well with Pilau, such as Kachumbari or a specific beverage.

**Visualization (December):**

![Sales & Quantity Sold Per Item In October](images/Sales%20&%20Quantity%20Sold%20Per%20Item%20In%20December.png)

**Interpretation & Insights (November):** 
* Chapati and Tea remain the dominant sellers in December, maintaining their strong performance.  
* Uji sales have decreased, a trend that needs attention. 
* Pilau continues its steady growth, showing promising potential. 
* Lentils experienced slight growth, suggesting some positive momentum.  
* Fries sales dropped further, continuing a concerning downward trend.

**Actionable Recommendations (December):**
* **Chapati and Tea:** Continue monitoring the performance of Chapati and Tea, your star items.  While they're consistently strong, explore opportunities for seasonal promotions or limited-time offers to keep them top-of-mind for customers.  

* **Uji:** The decrease in Uji sales in December is a red flag.  Investigate the potential causes:
1) Were there any changes in the recipe or preparation of Uji? Ensure consistency in quality.
2) Revisit Uji's availability throughout the day. Are there any stockouts or times when it's not readily available?
3) Actively solicit customer feedback on Uji. Are there any complaints or suggestions for improvement?
* **Pilau:** Its continued growth is a positive sign.  Capitalize on this momentum:

1) Targeted Marketing: Run targeted marketing campaigns for Pilau, perhaps focusing on social media or local advertising.
Menu Enhancements: Explore offering variations of Pilau (e.g., vegetable pilau, chicken pilau) to broaden its appeal.

* **Lentils:** The slight growth in Lentils sales is encouraging.  Consider incorporating Lentils into combo meals or offering them as a featured side dish.  Highlight their nutritional value.

* **Fries:** The persistent decline in Fries sales is a major concern.  A thorough review is necessary:

1) Check on Fries availability throughout the day. Are there any stockouts or times when it's not readily available?
2) If the issues with Fries cannot be effectively addressed, consider replacing them with a more profitable and popular alternative. This might involve introducing a new side dish or partnering with a local supplier for a higher-quality offering.
3) Creating attractive packages or bundles that include Fries alongside other popular items. This could increase Fries sales by leveraging the popularity of other dishes.

**Overall Top Performer Analysis:**

Chapati and Tea are consistently top sellers. Uji and Fries show potential but suffer from inconsistent sales. Pilau exhibits potential growth in sales.

**Overall Recommendations:**
* Prioritize Chapati and Tea availability.
* Address Uji and Fries availability issues.
* Capitalize on Pilau's popularity, especially considering potential seasonal in December.

#### Which item categories contribute the most to total sales?

**Approach:** A column chart visualizes the percentage contribution of each category to total sales.

**Visualization:**

![category_contribution.png](images/Revenue%20Contribution%20by%20Major%20Item(Oct-Dec).png)

**Interpretation & Insights:** 
* **Complementary Effect:** The data clearly indicates that Chapati, Tea, and Lentils are key drivers of the business's success, likely due to their complementary nature. Customers frequently buy these items together, and this combination contributes significantly to the business's total sales.

**Actionable Recommendations:** 

* Create formal meal deals or combo packages featuring Chapati, Tea, and Lentils. Offer these bundles at a slightly discounted price compared to purchasing the items individually, incentivizing customers to buy the combination. Experiment with different bundle sizes to cater to individuals and groups.

* Actively promote these bundled meal deals in-store, on the menu. (e.g., "Save 10 Ksh when you buy the Chapati, Tea, and Lentils Combo" or " Buy 2 chapatis, Tea and Lentils and get one chapati for free").

* Optimize Bundle Pricing: Carefully analyze the pricing of the bundles to maximize profitability while still offering a compelling discount to customers.  Consider different pricing tiers for various bundle sizes.

Placement and Promotion:  Ensure that Chapati, Tea, and Lentils are prominently displayed on the menu, both individually and as part of the bundled deals.  Consider using menu design elements (e.g., boxes, highlights) to draw attention to the bundles.

Data Analysis: Continuously monitor the sales data for the bundled deals to assess their effectiveness.  Track which bundles are most popular and adjust pricing or offerings as needed.  Analyze if the bundles are increasing the average order value

### Order Insights

#### How do order types compare in terms of revenue?

**Approach:** A line chart compares revenue generated by each order type in each month.

**Visualization:**

![Dine_ In_revenue.png](images/Income%20Generated%20by%20dine_ins.png)
![Delivery_Revenue.png](images/Income%20Generated%20by%20Deliveries.png)

**Interpretation & Insights:**
* **Dine-In Revenue:** A slight but consistent downward trend was observed in dine-in revenue. This suggests potential challenges in this area and warrants further investigation
* **Delivery Revenue:** Delivery revenue showed strong initial growth from October to November, indicating increased utilization of the delivery service. However, the growth plateaued from November to December. While the overall trend is positive, strategies to maintain growth may be needed.
* **Potential Shift in Customer Behavior:** The contrasting trends may indicate a shift towards delivery and away from dine-in with customers preferring their food brought to them rather than them coming in to dine.


**Actionable Recommendations:**

**Dine-In Experience Optimization To address the declining dine-in revenue, focus on enhancing the overall dine-in experience:**
* **Customer Feedback:** Implement methods for gathering customer feedback (e.g., surveys, comment cards, online reviews) to understand the reasons for declining patronage. Are there issues with service, food quality, ambiance, or pricing?
* **Menu Innovation:** Introduce new menu items or seasonal specials to attract customers and keep the menu fresh and exciting. Consider offering promotions or special events to drive traffic during slower periods.
* **Loyalty Programs:** Implement a loyalty program to reward repeat dine-in customers and encourage them to return.

**Delivery Revenue Growth Strategies:**  *While delivery revenue showed initial growth, the plateau suggests a need for new strategies:*

* **Promotions:** Consider offering delivery-specific promotions or discounts.
* **Delivery Area Expansion:** Explore expanding the delivery area to reach a wider customer base.
* **Customer Feedback:** Gather feedback from delivery customers to identify areas for improvement in the delivery experience, such as delivery time, food packaging, and customer service.
* **Adapt to Customer Behavior Shift:**  Recognizing the shift towards delivery, the restaurant should:

1) If delivery is becoming a significant part of the business, consider investing in dedicated delivery resources, such as delivery vehicles or insulated delivery bags and/or delivery personnels.
Seamless Integration: Ensure a seamless integration between online ordering platforms, delivery services, and the restaurant's kitchen and operations. This will improve efficiency and customer satisfaction.


## Key Findings

* An increasing quantity sold without a proportional increase in revenue.
* Chapati and Tea are consistently the top-selling items, accounting for 30% of total revenue.
* Delivery income has increased by 40% over the three months, representing a significant growth opportunity.
* Uji and Fries have inconsistent sales due to availability issues, impacting potential revenue by an estimated 15%.

## Tools Used

* Google Sheets: Data cleaning, pivot tables, slicers, charting.

## Next Steps

* **Data Enrichment:** Incorporate customer demographics and feedback to understand customer preferences better.
* **Advanced Analysis:** Conduct market basket analysis to identify item combinations and optimize menu offerings.
* **Operational Improvements:** Address Uji and Fries availability issues. Explore targeted marketing campaigns for specific items or categories.
* **Delivery Optimization:** Analyze delivery times and customer feedback to improve delivery service efficiency.
