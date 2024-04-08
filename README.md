# Dahel_Northwind_Traders_Analysis_Internship
Dahel and Consultant Techies Internship: I'm working as a data analyst for Northwind Traders, a global import and export company that specializes in supplying high-quality gourmet food products to restaurants, cafes, and specialty food retailers around the world (*The picture below is gotten from OutSystems Website*). 

![](https://www.outsystems.com/Forge_CW/_image.aspx/Q8LvY--6WakOw9afDCuuGWJZr_aUfmcmCS7P-ESVEKo=/northwind-db-2023-01-04%2000-00-00-2024-02-26%2009-48-44)

## Introduction

This is an analysis of the sales performance of Northwind Traders. It is done by analyzing data from customers table, employees table, categories table, products table, orders table, order details table, and shippers table. The entire project was carried out with the use of Excel.                                             . 

## Problem Statement

The goal of this analysis is to:

- Determine noticable sales trends over time
- Know which are the best and worst selling products
- Identify the company's key customers
- Determine shipping costs across providers
- Finally, the goal is to create data-driven plans that can aid in increasing sales, improving customer satisfaction, and driving the company's growth

## Skills and Concepts Demonstrated:







   ---
  ## Data Source:
  
The dataset for the work is gotten from Dahel and Consultant Techies while its original source is from Microsoft licensed by Public Domain. It consist of 2,985 records and 28 fields of data. I studied the dataset well and its attached dictionary to gain proper insight into the dataset. You can find a link to download the dataset [here:](https://mavenanalytics.io/challenges/maven-northwind-challenge/24)

   ---

## Data Transformation:

The dataset were opened using Excel and then imported into Power Pivot and Power Query for further transformation.
Using data analysis expressions, new columns were calculated.
* A calculated column for revenue generated was created using =order_details[unitPrice]*order_details[quantity]* (1-order_details[discount]).
* A calculated column for days it took for shipping was created using =orders[shippedDate]-orders[orderDate].




The transformation views are displayed below:



![image](https://github.com/RemedyData/Dahel_Northwind_Traders_Analysis_Internship/assets/137626163/a2f1e549-48f6-4b38-af02-c1f9c6780f38)



![image](https://github.com/RemedyData/Dahel_Northwind_Traders_Analysis_Internship/assets/137626163/b04d7de1-5524-4da4-91d9-4382d9cf2098)


---

## Data Modelling:

Tables were automatically joined by creating relationships with them as Power Pivot does this intelligently. However, as someone that understands the dataset and want to get specific insights and information, I had to create other relationships  between the tables and model created using a common key (primary key to foreign key) and measures to enable me derive desirable results. 

Below is the created model:


![Power Pivot-1](https://github.com/RemedyData/Dahel_Northwind_Traders_Analysis_Internship/assets/137626163/d5b39b39-5142-4566-b2c8-648ebbd04f5b)




## Data Analysis and Visualization:

Pivot chart was used to show the trend in sales over time. 


## Features of the Report:
The chart conveys information about the following key areas:
- Revenue
- Order date(Month,Year)
- Sales trend



![image](https://github.com/RemedyData/Dahel_Northwind_Traders_Analysis_Internship/assets/137626163/2582a7cc-678d-4e10-b2c7-8ff6df11c5ae)



## Analysis

Summary of the insights gained into the company's performance: 

▪︎A total revenue of £1.27 million was realized between the year 2013-2015.

▪︎With 77 products which Northwind Traders had in stock, they were able to receive 830 orders within the year 2013-2015.

▪︎£64,942 was spent on shipping of products within the year 2013-2015.

▪︎Northwind Traders had a total number of 91 customers from 21 different countries within the year 2013-2015.

▪︎Highest revenue was made in April, 2015 with a sum of £124,000.

▪︎Lowest revenue was made in May, 2015 with a sum of £18,000.

▪︎QUICK-stop happens to be the company with the most highest leads generating a sum of £110,277 for Northwind Traders. 

▪︎Hungry Owl All-Night Grocers happens to be the company with the lowest leads generating a sum of £49,979 for Northwind Traders. 

▪︎Beverages happens to be the product with the highest revenue taking 21.16% of the total revenue.

▪︎Grains and Cereals happens to be the product with the lowest revenue taking 7.56% of the total revenue 

▪︎USA, Germany, Austria happens to be the top 3 countries with the highest revenue. 

▪︎United Package has the highest orders followed by Federal Shipping then Speedy Express.


## Recommendation

- There are no doubts that the business is performing well as there are potential leads within the company yielding higher returns.

- The grains and cereals subcategories are not doing much in sales. Strategies to increase the sales should be made like "discounted bundle-selling" where for any purchase of beverages which happens to be the product with the highest revenue, grains or cereals will be added as an offer in addition to the beverages but at a discounted price which will be cheaper compared to when they are buying the grains or cereals as a stand-alone product.

 - Use database to gather customer feedback to get their experiences about the product or services. This information can be used to identify areas for improvement.

 - Understand Customers purchasing pattern by carrying out an analysis on this. This will tell what customers are buying, when they are buying  and how to promote the goods to the customers.

 - It is suggested that 8 products be discontinued so as increase the company's leverage. 


---

### Thank you for reading.

I am open for entry-level to mid-level data anlalyst role.

Let us have discussion about your company and industry now!
