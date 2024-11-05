# CAPSTONE PROJECT

## SALESDATA
[Project Overview](#project-overview)

[Column Descriptions](#column-descriptions)

[Data Source](#data-source)

[Tools Used](#tools-used)

 [Data Cleaning and Preparations](#data-cleaning-and-preparations)
 
[Exploratory Data Analysis](#exploratory-data-analysis)
 
 [Data Analysis](#data-analysis)
 
 [Data Visualization](#data-visualization)
 
 [My Result](#my-result)

### Project Overview
---
 This dataset contains transactional sales data, offering a comprehensive view of customer orders. It includes details on products, regions, and revenue, making it ideal for analyzing sales trends and regional performance. The dataset enables insights into revenue drivers and identifies high-demand products.

### Column Descriptions
---



### Tools Used
---
- Microsoft Excel [Download Here](https://www.microsft.com)
1. For data cleaning
2. summarizations
3. Visualization.

- SQL: used queries for data cleaning.

- Power BI:  both data cleaning, Summarization and visualization.

### Data cleaning and preparation 
---
 we perform the following action;

1. Data loading and Inspection
2. Handling missing variables
3. Data Cleaning and Formatting

### Exploratory Data Analysis:
---
This involved the exploratory of the Data to answer some questions about the data such as;
- Retrieve the total number of customers from each region.
- Find the most popular subscription type by the number of customers.
- Find customers who canceled their subscription within 6 months.
- Calculate the average subscription duration for all customers.
- Find customers with subscriptions longer than 12 months.
- Calculate total revenue by subscription type.
- Find the top 3 regions by subscription cancellations.
- Find the total number of active and canceled subscriptions.


### Data Analysis
---
This is where we include some basic lines of code or queries or even some of the DAX expressions used during the analysis

```SQL
SELECT * FROM CAPSTONE DATA 

````SELECT Product, SUM(Quantity * UnitPrice) AS TotalSale
FROM [LITA Capstone Dataset]
GROUP BY Products 
```


### Data Vitualization
---
![SQL SALE DATA](https://github.com/user-attachments/assets/7e5fe9ec-7825-4521-81cd-c332cce8e5fd)



![Pivot Tables SalesData](https://github.com/user-attachments/assets/df608dbe-13dd-4afc-a68a-f54d463fbf33)



### My Result
---
Our analysis of sales data highlights clear patterns in customer preferences and purchasing behavior across products, time periods, and regions.
Key findings include:
- Product Performance: Shoes emerged as the top-selling item with over 600,000 units sold, outperforming all other categories. In contrast, socks ranked as the lowest-selling product with approximately 180,000 units sold, though they maintained steady demand.
- Monthly and Quarterly Trends: Sales activity peaked in February, marking the highest monthly performance of the year. Strong sales were observed in Q1 and Q2; however, a decline became evident from Q3 onward, with sales decreasing by over 50% in Q4 as summer transitioned to fall.
- Regional Distribution: Regional sales data shows the South led with 44% of total sales, followed by the East (23%), North (18%), and West (14%). This regional breakdown suggests strong customer engagement in the South, with varying levels across other regions.
- Price Sensitivity and Customer Preference: Higher-priced products outperformed lower-priced alternatives, indicating a customer preference for perceived quality and a willingness to invest more for value.
- Average Sales Rate: The average sales rate was 211.78%, underscoring robust customer engagement throughout the year.

Overall, these insights provide valuable guidance for inventory management, pricing strategy, and targeted regional marketing efforts.
