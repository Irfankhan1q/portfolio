# Sales Analysis and Forecasting

## Project Overview
This project analyzes and forecasts sales data using SQL, Python (Prophet Model), and Tableau. The aim is to uncover insights about customer behavior, product demand, and sales trends, and to make predictions for future sales.

## Objectives
- Extract and transform data using SQL.
- Analyze purchasing behavior, product performance, and sales trends.
- Forecast future sales using time-series analysis with Prophet.

## Data
The dataset includes:
- **Transaction Details**: Invoice ID, Branch, City, Customer_type, Gender, Product_line, Date, and Time.
- **Financials**: Unit_price, Quantity, Tax, Total, Cost of Goods Sold (cogs), gross_margin_percentage, gross_income.
- **Customer Feedback**: Payment method and Rating.

## Key Analyses
1. **Customer Purchasing Behavior**: Comparison by Customer_type and Gender.
2. **Product Demand**: Average quantity sold per Product_line.
3. **Sales Trends**: Monthly and quarterly patterns.
4. **Revenue by Location**: Analysis by Branch and City.
5. **Payment Preferences**: Breakdown by payment method.
6. **Customer Satisfaction**: Ratings per Product_line.

## Tools Used
- **SQL**: Data extraction, transformation, and cleaning.
- **Tableau**: Visualizing sales trends and customer behavior.
- **Python (Prophet)**: Forecasting future sales trends.
- **Excel**: Data Preprocessing and cleaning using Employee data

## Results
1. **Seasonal Sales Trends**: Peaks in January, lows in February.
2. **High-Demand Products**: Food and Beverages generate the most revenue.
3. **Customer Demographics**: Female Members contribute most to sales.
4. **Payment Preferences**: Cash is most popular.
5. **Customer Satisfaction**: Highest ratings for Fashion Accessories, lowest for Health and Beauty.

## Forecasting with Prophet
Using Prophet, we forecasted sales for 60 days. The model reveals a stable initial period, followed by a peak and drop, potentially due to seasonal demand or events.

## Recommendations
1. Increase marketing efforts during peak sales months.
2. Focus on high-revenue product lines.
3. Enhance loyalty programs for Normal customers.
4. Expand in high-revenue locations.
5. Improve customer satisfaction in low-rated product lines.
