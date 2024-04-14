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

To build an actionable roadmap for upcoming years based on the metrics provided in the dashboards, we can frame key questions around each metric to guide strategic planning and decision-making. 
These metrics provide a starting point for analyzing the data presented in the dashboards and developing actionable strategies for future growth and optimization.

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
1. **KPI Comparison to Previous Year:**
	- Insight: Understanding how key performance indicators (KPIs) such as Cost of Goods, Revenue, Quantity, Profit, Profit Margin, and Transaction perform compared to the previous year.
	- Recommendation: Identify factors driving changes in metrics and adapt strategies accordingly. For instance, if Profit Margin decreased, assess factors like increased COGS or decreased revenue.

2. **Yearly Performance Metrics (Above Average Years):**
	- Insight: Identifying years with exceptional performance in Total Revenue, Profit, and Transaction.
	- Recommendation: Analyze strategies implemented during these high-performing years to replicate success in subsequent years. Implement targeted marketing campaigns or product enhancements.

3. **Monthly Profit Trends:**
	- Insight: Analyzing monthly profit trends to uncover seasonal patterns or fluctuations.
	- Recommendation: Utilize insights to adjust inventory levels, marketing strategies, or promotions based on seasonal demand fluctuations.

4. **Profit by Week Type:**
	- Insight: Understanding profit variances across different week types.
	- Recommendation: Tailor promotions or events to capitalize on days or periods driving higher profits. For instance, offer weekend-specific promotions if weekends consistently yield higher profits.

5. **Quarterly Profit Analysis:**
	- Insight: Evaluating profit performance by quarter.
	- Recommendation: Identify quarters with consistent outperformance and investigate factors contributing to success. Adjust inventory levels or marketing strategies accordingly.

6. **Profit by Weekday:**
	- Insight: Examining profit trends specific to weekdays.
	- Recommendation: Optimize staffing and inventory management based on weekday profit trends. For example, allocate more resources for high-profit weekdays.


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
