# Super-Store-sales Analysis Power Bi Project

**Title**: Super store sales analysis

**Level**: Beginner

**Dashboard Link**: https://app.powerbi.com/links/zKkehFs7NB?ctid=51302999-bb18-4fba-98bf-3a7ab3f07f13&pbi_source=linkShare&bookmarkGuid=36833ecf-af23-447d-9efe-f75369783984

## Overview
The Superstore Sales Dashboard provides a comprehensive view of sales performance across various dimensions, including region, category, sub-category, and time. The primary goal of the dashboard is to enable stakeholders to make data-driven decisions by offering actionable insights.

## Steps Followed

1.load data into Power Bi Desktop,Dataset is a CSV file. 

2.Open power query editor & in view tab under Data preview section ,check column distribution.

3.Also since by default profile will be opended only for 1000 rows so you need to select column profiling based on entire dataset.

4.It was observed that in none of the columns error & empty values were present except column named arrival delays.

5.For calculating average delay time null values were not taken into accounts as only 1% values are null in this column.

## Data Transformation

Data preparation involves the following steps:

1.**Data Cleaning**:
	
Removal of duplicate records.

Handling of missing values by imputation or exclusion.

2.**Data Modeling**:

Creation of relationships between tables (e.g., Orders, Products, Customers).

Use of DAX (Data Analysis Expressions) for calculated measures like Total Sales, Profit Margin, and Average Order Value.

3.**Data Enrichment**:

Adding calculated columns (e.g., Year, Month, Quarter from Order Date).

Categorizing products into high, medium, and low profitability groups.

## Dashboard Features

**Key Metrics**

The dashboard highlights the following key metrics:

**Total Sales**: Aggregate sales revenue.

**Total Profit**: Aggregate profit earned.
 
**Profit Margin**: Ratio of profit to sales.

**Customer Segments**: Analysis of high-value customers.

A card visual was used to represent count of total sales.

![Screenshot 2025-01-08 121112](https://github.com/user-attachments/assets/50d6140b-ddca-4d60-8826-411a2311461e)
 
A card visual was used to represent the count of total profit.
 
  ![Screenshot 2025-01-08 121127](https://github.com/user-attachments/assets/29ecccf4-ed87-45bc-b495-005b26068926)

A card visual was used to represent count of total orders.

 ![Screenshot 2025-01-08 121054](https://github.com/user-attachments/assets/95baa59b-5ea5-40db-8414-cf7869fb2843)

 Creating a new column following DAX expression was write.
 
Following DAX expression was written to find Sum Of Average Delivery.

         AvgDelivery = DATEDIFF(SuperStore_Sales'[Order Date], 'SuperStore_Sales'[Ship Date],DAY)

 ![Screenshot 2025-01-08 121954](https://github.com/user-attachments/assets/3d935ace-d19d-4fe7-962d-f71dfffef0c5)

## Publishing To Power Bi

![Screenshot 2025-01-07 191740](https://github.com/user-attachments/assets/1ef14271-15fa-477e-98eb-7213f63c6307)

# Snapshot Of Dashboard (Power Bi service)

![Screenshot 2025-01-08 121019](https://github.com/user-attachments/assets/1d573fab-50f1-4f84-8cfc-37116d8d08a7)

# Visualizations

## SUPERSTORE SALES DASHBOARD

![Screenshot 2025-01-02 221550](https://github.com/user-attachments/assets/f45868c9-5598-4344-8037-f653410aba57)

## SUPERSTORE SALES FORCAST DASHBOARD

![Screenshot 2025-01-02 224641](https://github.com/user-attachments/assets/8a2f5158-8d1a-49a2-890a-9c7323fc5455)

The dashboard includes the following visual components:

1.**Sales Trend Analysis**:

Line chart showing monthly and yearly sales trends.

2.**Regional Performance**:

Map visualization depicting sales and profit by region.

3.**Category Performance**:

Bar charts showing sales and profit by category and sub-category.

4.**Profitability Analysis**:

Scatter plot of products by sales and profit.

5.**Customer Insights**:

Table or matrix showing top customers by sales and profit.

# Conclusion
The Superstore Sales Dashboard provides an intuitive interface for analyzing sales data and uncovering actionable insights. Proper maintenance and updates will ensure its continued relevance and utility for stakeholders.





