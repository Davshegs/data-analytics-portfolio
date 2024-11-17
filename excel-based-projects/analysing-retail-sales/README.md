# **Sales Performance Analysis for Superstore**

## **Overview**

This project evaluates sales performance, profitability, and other key metrics for a fictitious retail chain called Superstore. 
Using the provided dataset, various analyses were conducted to derive insights into sales trends, profit contributions, and average order values across multiple categories and segments. 
The findings aim to assist decision-making for improved operational efficiency and strategic planning.

## **Dataset Description**

The analysis used the superstore.xlsx dataset, which contained three sheets:

**Orders:** Detailed transactional data, including sales, products, and customer information.

**People:** Supervisory information by region.

**Returns:** Data indicating whether orders were returned.

## **Key Attributes Analyzed:**

**Orders:** Sales, profit, discount, categories, and order dates.

**People:** Supervisor for each region.

**Returns:** Returned orders.

The data was consolidated using VLOOKUP to merge relevant fields for a comprehensive dataset.

## **Analysis Objectives**

The analysis was conducted to answer the following key business questions:

1.What are the overall sales, profit, and profit margin for the store?

2.How do categories and segments contribute to profitability?

3.What are the sales trends over time, and which categories drive growth?

4.What is the forecast for future sales?

5.How does the average order value (AOV) vary across regions?

## **Analysis and Key Findings**

1.**Preparing the Data**

Data was merged across sheets to consolidate information.
	
Missing or inconsistent values were checked to ensure data quality.
	
2.**Order Dates and Statistics**

Date Range: Orders ranged from January 1, 2014, to December 31, 2017. There were no missing years.
	
## **Aggregate Metrics:**
	
*Total Sales:*  $2,297,200.86 
	
*Total Profit:*  $286,397.02 
	
*Overall Profit Margin:* 12.47%
	
3.**Profit Composition by Category and Segment**

**Segment Analysis:**
	
*Segments:* Three segments—Consumer, Corporate, and Home Office.
	
Consumer contributed the most profit during the last recorded full year.
	
**Category and Subcategory Analysis:**

*Subcategories driving profits varied by category:*

*Furniture:* Chairs contributed 44% of category sales.

*Office Supplies:* Storage contributed 31% of category sales.

*Technology:* Phones contributed 39% of category sales.

4.**Sales by Category Over Time**

Year-on-Year Growth:

The highest growth occurred in 2016, with Technology showing the highest percentage increase.


5.**Forecasting Future Sales**

A line chart of quarterly sales from 2014 to 2017 revealed:

*Highest Sales Quarter:* Q4 consistently had the highest sales.

*Lowest Sales Quarter:* Q1 consistently showed the least sales.

A linear trendline forecasted moderate sales growth but highlighted limitations in capturing seasonal variations.

6.**Analyzing Average Order Value (AOV)**

Average Order Value Calculation:

Formula: 

**AOV = Total Sales / Number of Orders**

​
## **Descriptive Statistics:**

Conducted using the Analysis ToolPak for summary metrics.

Distribution analysis showed AOV was skewed and not normally distributed.

## **Regional Comparison:**

Using t-tests, Kelly Williams (Central) had a marginally higher AOV than Chuck Magee (East) in 2017. However, small sample sizes could bias results.

## **Conclusion**

The analysis uncovered critical insights into Superstore's sales and profitability:

Consumer Segment and Technology Category are key drivers of profitability.

Seasonality affects sales, with Q4 being the most lucrative quarter.

Future sales show an upward trend but require more granular forecasting to capture seasonal effects.

Regional differences in AOV highlight potential areas for operational improvement.

## **Limitations**

Seasonal variations were not fully accounted for in the linear forecast.

Sample sizes for some regions were too small for robust statistical comparisons.

## **Recommendations**

Focus marketing efforts on Technology during Q4 to maximize revenue.

Investigate reasons behind regional differences in AOV for strategic improvements.

Use advanced forecasting models, such as ARIMA, for more accurate sales predictions.