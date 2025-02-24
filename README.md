# McDonald's Sales Analysis Project
## Project Overview:
This project focuses on analyzing McDonald’s US sales data using Excel to create an interactive, dynamic dashboard. The goal is to explore key sales metrics, item popularity, customer preferences, and time-based trends, offering actionable insights to support business decisions and strategy optimization.

Dataset Link: https://drive.google.com/drive/folders/1raeubcRpUisUUuDyY6ezvfc7VHHydpoV

## Dataset:
The dataset provides detailed information on orders, menu items, and the time of orders, enabling a comprehensive analysis of McDonald's sales performance across various dimensions.

## Data Cleaning:
- Removed duplicate records.
- Handled missing values using forward and backward fill methods to maintain data consistency.
- Corrected data types for all columns, especially date and time formats, aligning with the English US locale.

## Data Transformation:
- Created new columns such as @Exact Hours, @Meal of the Day, and @Time of Day based on order time.
- Merged menu item prices with order details using common keys like @item_id and @menu_item_id.
- Added features like @Day Name, @Month Name, @Day of Week, and @flagged orders as @Weekend or @Weekday.

## Data Analysis & Dashboard:
Using Power Pivot in Excel, relationships between tables were established, and the data model was used to create pivot tables and measures. This led to the development of a dynamic dashboard that provides visual insights into McDonald’s sales performance.

## Key Insights:
Sales by Time of Day: Peak sales occur during lunch (12 PM - 2 PM) and dinner (6 PM - 8 PM).
Top 5 Menu Items: The Meatball Marinara is the top-selling item, generating the highest revenue.
Revenue by Category: The Burger category contributes the most to total revenue, followed by Chicken and Fries.
Sales Trends: Weekend sales are higher, with Saturday showing the highest sales volume.
Order and Revenue Correlation: Higher order volumes correspond with higher revenue generation.
## Key Questions Answered:
What is the total sales revenue for each category of menu items?
How many orders are placed each day?
Which menu item is the most frequently ordered?
How does the revenue compare over months for each category?
What is the average number of items per order?
How do sales volumes vary by time of day and day of the week?
How does sales performance differ across weekdays and weekends?
What are the sales and revenue trends for the top 5 menu items?
## Strategic Recommendations:
Optimize Pricing Strategy: Review the pricing of top-selling and low-revenue items to improve profit margins.
Promote Low-Performing Categories: Target promotions for categories like Shakes and Sides to drive sales growth.
Midweek Promotions: Introduce special offers to boost sales during midweek, especially on Wednesdays when sales typically dip.
## Conclusion:
This project demonstrates the power of data-driven insights for improving operational efficiency and revenue strategies at McDonald's. The dashboard serves as a powerful tool for decision-makers to monitor performance, identify areas for improvement, and develop targeted marketing campaigns.
