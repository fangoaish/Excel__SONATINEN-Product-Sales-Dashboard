# Sales Product Performance Dashboard

## Project Overview

The Sales Product Performance Dashboard aims to provide comprehensive insights into the sales performance of products across various dimensions such as time, geography, and customer demographics. Utilizing data from six separate tables, the dashboard will offer a holistic view of sales metrics and trends.

### Dashboard 1 - Main Metrics Dashboard:

Dashboard - 1
1. **KPI Comparison to Previous Year**:
	- Cost of Goods(COGS), Revenue, Quantity, Profit, Profit Margin, and Transaction compared to the previous year.
		- How did our Cost of Goods, Revenue, Quantity, Profit, Profit Margin, and Transaction metrics perform compared to the previous year?
		- What factors contributed to any significant changes in these metrics compared to the previous year?
2. **Yearly Performance Metrics(Above Average Years)**:
	- Total Revenue, Profit, and Transaction for years exceeding the average performance.
		- Which years have exceeded the average performance in terms of Total Revenue, Profit, and Transaction?
		- What strategies or initiatives were implemented during these high-performing years that contributed to their success?
3. **Monthly Profit Trends**:
	- Analyzing profit trends monthly.
		- What are the trends in monthly profit performance? Are there any seasonal patterns or fluctuations that need attention?
		- How do external factors such as market conditions or consumer behavior impact monthly profit trends?
4. **Profit by Week Type**:
	- Assessing profit based on different week types.
		- How does profit vary across different week types (e.g., weekdays vs. weekends)?
		- Are there specific days or periods within the week that consistently drive higher profits?
5. **Quarterly Profit Analysis**:
	- Evaluating profit performance every quarter.
		- How does profit performance vary from quarter to quarter?
		- Are there specific quarters that consistently outperform others, and if so, what factors contribute to their success?
6. **Profit by Weekday**:
	- Examining profit trends specific to weekdays.
		- What are the profit trends specific to weekdays?
		- Are there particular weekdays that consistently generate higher profits, and if so, why?
<img width="1377" alt="Dashboard-1" src="https://github.com/fangoaish/Excel__SONATINEN-Sales-Product-Performance-Dashboard/assets/51399519/0ac81010-0fa7-46ce-b894-788ae83fba7a">


### Dashboard 2 - Product Performance Dashboard:
Dashboard - 2
1. **Top 5 Profitable Products (% Contribution and Others)**:
	- Identifies the five most profitable products and their contribution as a percentage of total profits, with insights into the rest.
		- Which products are the top performers in terms of profitability, and what percentage of total profits do they contribute?
		- Are there opportunities to optimize product offerings or pricing strategies to further enhance profitability?
2. **Top 5 Profitable Customers (% Contribution and Others)**:
	- Highlights the top five high-profit customers, their percentage share of overall profits, and details about other customers' contributions.
		- Who are our highest-profit customers, and what percentage of overall profits do they contribute?
		- How can we deepen relationships with these key customers and attract similar high-value customers?
3. **Profit by Gender**:
	- Displays profit breakdown by gender, helping identify gender-based profit trends.
		- How does profit break down by gender, and are there any notable differences in purchasing behavior or preferences between genders?
4. **Profit by Product Color (Highlighting Best Sellers)**:
	- Analyzes profits associated with product colors, highlighting the best-selling colors for optimization.
		- Which product colors are the best sellers in terms of profitability, and are there opportunities to leverage this insight to optimize inventory or marketing efforts?
5. **Profit by Pricing Types**:
	- Examines profit variations based on pricing types, providing insights into pricing strategy effectiveness.
		- How do profit variations differ based on pricing types (e.g., regular price vs. discount)?
		- Are there pricing strategies that consistently drive higher profitability, and how can they be refined or expanded?
6. **Country-wise Profit (Custom Map)**:
	- Utilizes a custom map to visualize profit distribution by country, aiding in geographic targeting.
		- How is profit distributed geographically across different countries?
		- Are there untapped markets or regions with growth potential that warrant strategic focus?
7. **Profit by Age Groups**:
	- Segment profits into age groups to understand which age demographics contribute the most to profitability.
		- Which age demographics contribute the most to profitability, and are there opportunities to tailor products or marketing strategies to better resonate with these groups?
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

  
## Data Preparation
- Use Power Query to remove unnecessary columns that are not relevant to the analysis and conduct Power Pivot to understand the relationship between each table
![Power Pivot](https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/a453fd90-eeb5-49b0-9d3e-3915f9480795)

- Use Power Query to sort the month sequences by month number so the pivot table starts from January
![sort by month number](https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/f92b35de-c4cf-4116-8816-da9778d78231)

- Add the the Age column from BirthDate column and categorize into different age group
![Date - Age - Transform - Total Years - Round Down](https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/796cf515-c959-4845-8b27-3dac374d92a4)
![Categorize Age Group](https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/b65b7ef1-cbcd-4b2c-a138-8ca2b0570f2a)

- Categorize pricing types into Premium Pricing: above $539.99 and Penetration Pricing: below $539.99
![Categorize pricing types](https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/a072928f-7e2c-4a87-9a02-0719697acc70)


## Data Exploration
- Use Power Pivot to calculate the measures for the following main metrics
  - Total Orders
  - Total COGS
  - Total Revenue
  - Total Profit
  - %Profit Margin
  - #Transaction
  - All Products
  - Sold Products
  - Unsold Products
![Calculation from Power Pivot for Measures](https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/6cc33549-c2ba-41db-9203-1c9b6eb736b2)
![All Measures](https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/91513f08-15e8-41ae-a552-fc68d4e86142)


- Use **IFs** function to coordinate with the option button so the graphics become dynamic
    - Switch between Revenue / Profit / #Transaction
<img width="1232" alt="IFS function to coordinate with option button" src="https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/7662adc5-411b-473e-aecb-9bc21da5d607">
<img width="288" alt="dynamic option button" src="https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/223e8b96-cde3-43f7-985e-4956ffaee67a">


- Use **IF** function to check if the #Transaction(Revenue / Profit) is above the average or not so we can highlight the above-average data with a different color in the graphic
<img width="1232" alt="IF function to check above average" src="https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/f6b112c3-170a-42dc-9618-f54ed3e433c1">
<img width="285" alt="Hight the data above average" src="https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/a3bbb715-a0d9-471f-a19e-2e9900854316">

- Use **VLOOKUp** function to make the comparison of the YoY performance of the main metrics such as Total Orders, Total COGS, Total Revenue, Total Profit, %Profit Margin, and #Transaction
- Use **IFERROR** function to manage the errors if the previous year's data is missing.
<img width="763" alt="Vlookup" src="https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/222e5dab-3041-4c40-acd5-9db63721c7c1">

![YoY comparison](https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/d90b1a76-482b-42f2-adc9-0463401314e6)

- Use **Large** function to highlight the total profit of the Top 3 months
- Use **Index Match** to find out the Top 3 months
<img width="1068" alt="Highlight the Top 3 Months" src="https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/b104d7da-764b-499a-ad80-8d505ca63abf">
<img width="966" alt="Index Match to find out the top 3 months" src="https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/137ab680-23af-421f-9489-3cb1f4bdb3c6">


- Use **Index Match** to find out the corresponded age group
<img width="901" alt="Index Match to find  Age_Group" src="https://github.com/fangoaish/Excel__Sales-Product-Performance-Dashboard/assets/51399519/03c7fed1-9fd6-4a94-996a-c3e4f1416545">


## Conclusion
By streamlining data preparation, exploration, and visualization processes, the dashboard empowers organizations to identify trends, track performance metrics, and optimize strategies for success. 
