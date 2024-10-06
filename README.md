
# Christmas Sales Analysis Project

## Project Overview
This project involves a comprehensive analysis of Christmas sales data for November and December, using Power BI for data preparation, cleaning, and visualization. The dataset used is from the ONYX Challenge Data, which provided a rich source of information for this analysis.

## Table of Contents
1. [Business Understanding](#business-understanding)
2. [Data Understanding](#data-understanding)
3. [Data Preparation](#data-preparation)
4. [Data Analysis and Visualization](#data-analysis-and-visualization)
5. [Insights and Conclusions](#insights-and-conclusions)
6. [Dashboard](Dashboard)
7. [Future Work](#future-work)

## Business Understanding
The goal of this project is to analyze sales data during the critical holiday season to uncover valuable business insights. Key performance indicators (KPIs) such as Customer Lifetime Value (LTV), Average Transaction Value, Return Rates, and Customer Satisfaction were examined to understand customer behavior, sales trends, and operational efficiency.

## Data Understanding
The dataset includes the following fields:
- **TransactionID**: Unique identifier for each transaction
- **Date**: Date of the transaction (YYYY-MM-DD)
- **Time**: Time of the transaction (HH:MM:SS)
- **CustomerID**: Unique identifier for each customer
- **Age**: Age of the customer
- **Gender**: Gender of the customer (Male, Female, Other)
- **Location**: City or town where the purchase was made
- **StoreID**: Unique identifier for the store, if applicable
- **OnlineOrderFlag**: Boolean indicating if the order was online
- **ProductID**: Unique identifier for the product
- **ProductName**: Name of the product
- **Category**: Category of the product (e.g., Electronics, Clothing, Toys, Food, Decorations)
- **Quantity**: Number of items purchased
- **UnitPrice**: Price per unit of the product
- **TotalPrice**: Total price for the product (Quantity * UnitPrice)
- **PaymentType**: Type of payment (e.g., Credit Card, Debit Card, Cash, Online Payment)
- **PromotionApplied**: Boolean indicating if any promotion was applied
- **DiscountAmount**: The amount of discount, if any
- **GiftWrap**: Boolean indicating if the product was gift-wrapped
- **ShippingMethod**: Method of shipping (e.g., Standard, Express, Overnight, if online)
- **DeliveryTime**: Number of days taken for delivery, if online
- **Weather**: General weather condition on the day of purchase (e.g., Snowy, Rainy, Sunny)
- **Event**: Special events on the purchase day (e.g., Christmas Market, Black Friday)
- **CustomerSatisfaction**: Customer satisfaction rating (1-5)
- **ReturnFlag**: Boolean indicating if the product was returned

## Data Preparation
Data preparation involved several steps:
1. **Data Cleaning**: Handling missing values, correcting data types, and removing duplicates.
2. **Data Transformation**: Creating new calculated fields such as TotalPrice, Customer Lifetime Value (LTV), and Average Transaction Value.
3. **Data Integration**: Combining data from different sources to create a comprehensive dataset.

## Data Analysis and Visualization
Using Power BI, various visualizations were created to analyze the data:
1. **Sales by Category**: Bar chart showing sales distribution across different product categories.
2. **Online vs. In-Store Sales**: Pie chart comparing online and in-store sales.
3. **Top Products**: Bar chart displaying the most sold products.
4. **Customer Demographics**: Pie charts and bar graphs showing age and gender distribution of customers.
5. **Customer Satisfaction**: Horizontal bar graph representing customer satisfaction ratings.
6. **Payment Methods**: Distribution of payment methods used by customers.
7. **Special Events Impact**: Analysis of sales during special events like Black Friday and Christmas Market.
8. **Shipping Methods**: Breakdown of shipping methods used for online orders.
9. **Regional Sales**: Map highlighting sales data across different regions.

## Insights and Conclusions
- **Total Sales**: $1,564,250
- **Total Quantity Sold**: 30,106
- **Number of Transactions**: 10,000
- **Maximum Discount Given**: 49.95%
- **Average Customer Age**: 44
- **Customer Lifetime Value (LTV)**: $6,593.74
- **Average Transaction Value**: $54.95
- **Return Rate**: 50.72%
- **Customer Satisfaction**: Average rating of 2.99

### Key Insights:
- Online orders accounted for 55% of total orders.
- "Electronics Products" were the most sold items.
- Females represented 33% and males 34% of the customers.
- Special events like Black Friday significantly boosted sales.
## Dashboard 📊  <br>
![image](https://github.com/user-attachments/assets/9aadc982-3549-4ad2-87fc-d7ff32bcb74b) <br>
![image](https://github.com/user-attachments/assets/2146ba0b-8490-4a4a-8ba8-ff59aa7b04ed) <br>
![image](https://github.com/user-attachments/assets/f7b43aac-06af-450f-a3da-c08eda046bd9) <br>

You can check the interactive dashboard from [here](https://www.linkedin.com/feed/update/urn:li:activity:7248744583482724354/).

## Future Work
- **Deeper Analysis**: Conduct more detailed analysis on customer behavior and preferences.
- **Predictive Modeling**: Use machine learning models to predict future sales trends.
- **Enhanced Visualizations**: Create more interactive and detailed visualizations.


