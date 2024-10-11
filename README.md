# Superstore-Report

## INTRODUCTION 
The Superstore Dataset, which is a US-based superstore that sells furniture, office supplies, and technology products, is one of the analytics projects I will be working on as part of the assessment for the PSP Analytics Data Science class. 

The superstore dataset includes shipping dates, sales, profit, and other data about the super store. The objective of this work is to analyse the Superstore's performance and to uncover insights to be used for the business growth. 

## DATA SOURCING 
The dataset that was utilised in this project was posted by MrZion Segun on the Data Science Class announcement 
channel.  

## DATA PREPARATION 
To begin, the dataset is imported  into PowerBI in Excel format. Import the data straight away or alter it to make it clean on PowerBi. In this instance, verification  that each column's format is accurate and any required corrections are made. To provide a more precise dataset for analysis, discrepancies in the columns are resolved as well.  

## DATA CLEANING AND TRANSFORMATION 

In this phase, it is verified that every column has the correct format and necessary corrections are made. To guarantee a more accurate dataset for analysis, column discrepancies are resolved. The Sales, Profit, as well as Discount columns are now formatted to show currency.  

## DATA EXPLORATION/VISUALIZATION 

At this point, charts and tiles are used to respond to particular business queries for sale performance analysis. These are a few of the queries that are asked: 

- What category has the highest order totals?
- What is the profit margin that each category has achieved?
- Which city has the highest order volume for the store?
- In what subcategory are there more sales?
- Which city generates more revenue?

## KEY PERFORMANCE INDICATORS 

Setting the KPI (Key Performance Indicators) is necessary before we can proceed with answering the question. The profit, quantity, margin, discount, and sales are among the KPIs. To compute total sales, profit, quantity, discount, and to determine our profit margin, measures are created and DAX is used. 

- Sales: The SUM function is used to determine the total sales. 
- Profit Margin: The profit margin is calculated by dividing the entire profit by the total sales and multiplying the result by 100.
- Quantity: The amount in the dataset is the sum of its parts.
- Profit: The profit is the addition of its parts.
- Discount: Total discounted amount in the dataset as a sum  

**NOTE:**
For visualising the KPI, the KPI tile is employed. Moreover, the Card tile is an option. 

1. In what category are the highest orders found? 
The "Category" column and the "Quantity" measure can be related using the clustered column bar to get the highest order.

2. What is the profit margin that each category has made? 

3. Which city has the highest order volume for the store? 

4. In what subcategory are the most sales? 

5. Which city generates higher sales? 


## CONCLUSION 

So far, analysis on the superstore dataset and valuable insights through the business questions has been achieved. Based on these findings, data-driven recommendations can be provided to help for business growth. The resulting dashboard built from powerbi is shown below:

