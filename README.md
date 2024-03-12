# Sales Product Performance Dashboard

## Project Overview

The Sales Product Performance Dashboard aims to provide comprehensive insights into the sales performance of products across various dimensions such as time, geography, and customer demographics. Utilizing data from six separate tables, the dashboard will offer a holistic view of sales metrics and trends.

### Dashboard 1 - Main Metrics Dashboard:
- Create visualizations for main metrics including
  - **Total Orders**
  - **Total COGS**
  - **Total Revenue**
  - **Total Profit**
  - **% Profit Margin**
  - **# Transaction**
- Implement time slicers for filtering data by
  - **Months** (Jan- Dec)
  - **Year** (2015-2018)
  - **Country** (Australia, Canada, France, Germany, United Kingdom, United States)
- Develop visualizations for **Weekday**, **Monthly**, and **Quarterly** views of Total Profit
<img width="1377" alt="Dashboard-1" src="https://github.com/fangoaish/Excel__SONATINEN-Sales-Product-Performance-Dashboard/assets/51399519/0ac81010-0fa7-46ce-b894-788ae83fba7a">

### Dashboard 2 - Product Performance Dashboard:
- Analyze the Top 5 Profitable Products and visualize their performance
- Compare the Profit Share of the Top 5 Products vs. Others
- Provide an overview of Total Products, Sold Products, and Unsold Products
- Display Total Profit Share by Product Pricing Strategy (Premium Pricing: above $539.99, Penetration Pricing: below $539.99)
- Analyze Profit by Gender and Age Group contribution to Total Profit
- Visualize Total Profit by Countries

<img width="1373" alt="Dashboard 2" src="https://github.com/fangoaish/Excel__SONATINEN-Sales-Product-Performance-Dashboard/assets/51399519/80efffeb-06a0-4006-bd68-ed6b1bc6add2">


## Project Steps
1. Data Gathering
2. Data Preparation Using Power Query, Advanced Formulas and Functions
3. Exploratory Data Analysis
4. Data Visualizations and Dashboard Build using **Pivot Tables**, **Pivot Charts**, **Timeline**, **Slicers** and **Macro**

## Data Sources
The data source is a fictitious product sales dataset.
  - SONATINEN.csv

The data contains six separate tables:
- FactInternetSales, DimProduct, DimSalesTerritory, DimDate, DimCustomer and DimGeography
  - The **FactInternetSales** table is the _fact table_
  - The **DimProduct**, **DimSalesTerritory**, **DimDate**, **DimCustomer** and **DimGeography** tables are the _dimension tables_.

  
## Data Preparation
- Use Power Query to remove unnecessary columns that are not relevant to the analysis and conduct Power Pivot to understand the relationship between each table
![Power Pivot](https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/a453fd90-eeb5-49b0-9d3e-3915f9480795)

- Use Power Query to sort the month sequences by month number so the pivot table starts from January
![Sort the month sequence](https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/e60e2b05-247f-48b9-8a52-2f79fc76c047)
![sort by month number](https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/f92b35de-c4cf-4116-8816-da9778d78231)

- Add the the Age column from BirthDate column and categorize into different age group
![Date - Age - Transform - Total Years - Round Down](https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/796cf515-c959-4845-8b27-3dac374d92a4)
![Categorize Age Group](https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/b65b7ef1-cbcd-4b2c-a138-8ca2b0570f2a)

- Categorize pricing types into Premium Pricing: above $539.99 and Penetration Pricing: below $539.99
![Categorize pricing types](https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/a072928f-7e2c-4a87-9a02-0719697acc70)


## Exploratory Data Analysis
The primary objective of the Coffee Sales Dashboard is to provide comprehensive insights into our coffee sales performance, enabling effective decision-making and strategy formulation. The dashboard leverages various data manipulation and lookup techniques to present a holistic view of our sales operations. The following guidelines outline the specific objectives and functionalities of the dashboard:

- **Data Integration**: Integrate data from orders, customers, and products tables to provide a consolidated view of sales transactions, customer information, and product details.

- **Customer Information** Lookup: Utilize XLOOKUP to efficiently retrieve the full customer name and email address from the customers table and incorporate them into the orders table, enhancing customer-centric analysis and communication.

- **Country Mapping**: Employ XLOOKUP to map the country of the customer from the customers table to the orders table, facilitating regional sales analysis and targeted marketing strategies.

- **Product Details Integration**: Utilize dynamic INDEX MATCH formulae to seamlessly integrate coffee type, roast type, size, and unit price values from the products table into the orders table. Ensure correct cell locking to automate formula application across the dataset.

- **Sales Calculation**: Calculate sales revenue by multiplying the unit price with the quantity sold, providing insights into revenue generation and product performance.

- **Standardization of Coffee Types**: Utilize multiple IF functions to standardize coffee type and roast type names, ensuring consistency in reporting and analysis.

- **Loyalty Card Status Lookup**: Utilize XLOOKUP to incorporate loyalty card status from the customers table into the orders table, enabling targeted marketing campaigns and customer loyalty analysis.

By adhering to these guidelines, the Coffee Sales Dashboard aims to empower stakeholders with actionable insights, foster informed decision-making, and drive business growth in the competitive coffee market landscape.

