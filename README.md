# Sales Product Performance Dashboard

## Project Overview

The Sales Product Performance Dashboard aims to provide comprehensive insights into the sales performance of products across various dimensions such as time, geography, and customer demographics. Utilizing data from six separate tables, the dashboard will offer a holistic view of sales metrics and trends.

### Dashboard 1 - Main Metrics Dashboard:
1. **KPI Comparison to Previous Year**:
	- Cost of Goods(COGS), Revenue, Quantity, Profit, Profit Margin, and Transaction compared to the previous year.

2. **Yearly Performance Metrics(Above Average Years)**:
	- Total Revenue, Profit, and Transaction for years exceeding the average performance.

3. **Monthly Profit Trends**:
	- Analyzing profit trends monthly.

4. **Profit by Week Type**:
	- Assessing profit based on different week types.

5. **Quarterly Profit Analysis**:
	- Evaluating profit performance every quarter.

6. **Profit by Weekday**:
	- Examining profit trends specific to weekdays.
<img width="1377" alt="Dashboard-1" src="https://github.com/fangoaish/Excel__SONATINEN-Sales-Product-Performance-Dashboard/assets/51399519/0ac81010-0fa7-46ce-b894-788ae83fba7a">


### Dashboard 2 - Product Performance Dashboard
1. **Top 5 Profitable Products (% Contribution and Others)**:
	- Identifies the five most profitable products and their contribution as a percentage of total profits, with insights into the rest.

2. **Top 5 Profitable Customers (% Contribution and Others)**:
	- Highlights the top five high-profit customers, their percentage share of overall profits, and details about other customers' contributions.

3. **Profit by Gender**:
	- Displays profit breakdown by gender, helping identify gender-based profit trends.

4. **Profit by Product Color (Highlighting Best Sellers)**:
	- Analyzes profits associated with product colors, highlighting the best-selling colors for optimization.

5. **Profit by Pricing Types**:
	- Examines profit variations based on pricing types, providing insights into pricing strategy effectiveness.

6. **Country-wise Profit (Custom Map)**:
	- Utilizes a custom map to visualize profit distribution by country, aiding in geographic targeting.

7. **Profit by Age Groups**:
	- Segment profits into age groups to understand which age demographics contribute the most to profitability.
<img width="1337" alt="Dashboard 2" src="https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/361e17f8-52e9-47c4-9e58-52ffc31c2b94">


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

## Data Preparation:
![Power Pivot](https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/a453fd90-eeb5-49b0-9d3e-3915f9480795)
- Utilize **Power Query** to clean and prepare data.
- Utilize **Power Pivot** for understanding relationships between tables.
- Utilize the **IFs function** for dynamic graphics coordination.
- Use **VLOOKUP** for year-over-year (YoY) performance comparison.
- Manage errors with the **IFERROR function**.
- Highlight top performers using the **LARGE function**.
- Use **INDEX MATCH** to find the top months and corresponding age groups.
  

## Exploratory Data Analysis

### Dashboard 1 - Main Metrics Dashboard:
1. ### Yearly Performance Analysis
	- **Revenue and Profit by Year**
		- 2015-2018 saw a steady increase in revenue and profit, peaking in 2017 with over $102 million in revenue and a profit of $42.55 million.
		- Profit margins remained relatively stable (~41%), indicating consistent operational efficiency.
	- **Above Average Years (Revenue > $76.77M Average)**
		- 2017 and 2018 both exceeded the average, contributing 66.5% of the total revenue and 67.1% to overall profit during the observed period.

2. Monthly and Quarterly Trends
Top Performing Months
May, June, and December were top performers, contributing significantly to the annual profit with peaks during the mid and end of the year, likely reflecting seasonal sales increases.
Quarterly Analysis
Q2 was the highest performing quarter, suggesting a strategic opportunity for targeted marketing and sales initiatives during this period.
Weekday and Weekend Performance
Profit by Week Type
Weekdays significantly outperformed weekends, making up 71.8% of total profit.
Top weekdays for profit were Wednesday, Tuesday, and Thursday.












### Dashboard 2 - Product Performance Dashboard:
1. **Top 5 Profitable Products & Customers:**
	- Insight: Identifying top-performing products and customers contributing to overall profitability.
	- Recommendation: Develop strategies to leverage high-profit products and nurture relationships with key customers. Offer personalized promotions or loyalty programs.

2. **Profit by Gender:**
	- Insight: Analyzing profit breakdown by gender to uncover purchasing behavior differences.
	- Recommendation: Tailor marketing messages and product offerings to align with gender preferences, maximizing profitability.

3. **Profit by Product Color & Pricing Types:**
	- Insight: Understanding profitability associated with product colors and pricing strategies.
	- Recommendation: Optimize inventory based on popular product colors and refine pricing strategies to maximize profitability.

4. **Country-wise Profit & Age Groups:**
	- Insight: Visualizing profit distribution by country and age groups.
	- Recommendation: Identify untapped markets or demographics with growth potential. Tailor marketing efforts and product offerings to resonate with profitable age groups.


## Conclusion
By streamlining data preparation, exploration, and visualization processes, the dashboard empowers organizations to identify trends, track performance metrics, and optimize strategies for success. 
