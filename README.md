# Super-Store-sales Analysis Power Bi Project

**Title**: Super store sales analysis

**Dashboard Link**: https://app.powerbi.com/links/zKkehFs7NB?ctid=51302999-bb18-4fba-98bf-3a7ab3f07f13&pbi_source=linkShare&bookmarkGuid=36833ecf-af23-447d-9efe-f75369783984

## Overview
The Superstore Sales Dashboard provides a comprehensive view of sales performance across various dimensions, including region, category, sub-category, and time. The primary goal of the dashboard is to enable stakeholders to make data-driven decisions by offering actionable insights.

# Steps Followed

1.load data into Power Bi Desktop,Dataset is a CSV file. 

2.Open power query editor & in view tab under Data preview section ,check column distribution



# Data Transformation

Data preparation involves the following steps:
1.	**Data Cleaning**:
o	Removal of duplicate records.
o	Handling of missing values by imputation or exclusion.
2.	**Data Modeling**:
o	Creation of relationships between tables (e.g., Orders, Products, Customers).
o	Use of DAX (Data Analysis Expressions) for calculated measures like Total Sales, Profit Margin, and Average Order Value.
3.	**Data Enrichment**:
o	Adding calculated columns (e.g., Year, Month, Quarter from Order Date).
o	Categorizing products into high, medium, and low profitability groups.

# Dashboard Features

**Key Metrics**

The dashboard highlights the following key metrics:

**Total Sales**: Aggregate sales revenue.

 ![Screenshot 2025-01-08 121112](https://github.com/user-attachments/assets/50d6140b-ddca-4d60-8826-411a2311461e)
 
 **Total Profit**: Aggregate profit earned.
 
 ![Screenshot 2025-01-08 121127](https://github.com/user-attachments/assets/29ecccf4-ed87-45bc-b495-005b26068926)

**Total Orders**:

 ![Screenshot 2025-01-08 121054](https://github.com/user-attachments/assets/95baa59b-5ea5-40db-8414-cf7869fb2843)

 Creating a new column following DAX expression was write
 
Following DAX expression was written to find Sum Of Average Delivery

         AvgDelivery = DATEDIFF(SuperStore_Sales'[Order Date], 'SuperStore_Sales'[Ship Date],DAY)


# Visualizations

## SUPERSTORE SALES DASHBOARD

![Screenshot 2025-01-02 221550](https://github.com/user-attachments/assets/f45868c9-5598-4344-8037-f653410aba57)

## SUPERSTORE SALES FORCAST DASHBOARD

![Screenshot 2025-01-02 224641](https://github.com/user-attachments/assets/8a2f5158-8d1a-49a2-890a-9c7323fc5455)




