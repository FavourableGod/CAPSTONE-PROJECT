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

- OrderID: A distinct identifier assigned to each order.
- CustomerId: A distinct identifier for customers.
- Product: Items for sale/sold.
Region: The geographical location (e.g., North, South, East, West) 
- OrderDate: The date when the order was made.
- Quantity: The number of items purchased in an order.
- UnitPrice: The price per unit of the product.
- Total Sales: The total quantity of items/products sold.
-Revenue: The total sales value for the order, calculated as Quantity * UnitPrice

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
- Determine the total revenue generated for each product category.
- Count the number of sales transactions within each region.
- Identify the product with the highest total sales value.
- Compute the revenue generated for each individual product.
- Summarize monthly sales figures for the current year.
- List the top 5 customers based on their total spending.
- Calculate each region's contribution as a percentage of overall sales.
- Identify products that recorded no sales in the past quarter.




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
