# Dog Superstore Sales & Customer Insights Analysis


![excel-data-project](assets/images/Excel_Data_Project.png)




# Table of contents

- [Objective](#objective)
- [Data Source](#data-source)
- [Design](#design)
  - [Tools](#tools)
- [Development](#development)
  - [Pseudocode](#pseudocode)
  - [Data Cleaning](#data-cleaning)
- [Analysis](#analysis)
  - [Findings](#findings)
- [Conclusion](#conclusion)


# Objective

- What is the key pain point?
  
The Data Analyst must structure and analyze sales and customer data for Dog Superstore using Excel to improve customer segmentation, revenue forecasting, and product performance evaluation. The primary goal is to identify key customer demographics, purchasing behaviors, and sales trends. Data from multiple sources, including customer profiles, purchase history, income levels, and product categories, must be organized for accurate reporting. The analyst will develop an Excel-based system, including pivot tables and dashboards, to visualize sales distribution, top-selling products, and device usage for online orders. Additionally, the team wants to assess quarterly sales performance and determine whether specific customer groups drive higher revenue.


- What is the ideal solution?

The ideal solution is to develop a well-structured Excel-based system that organizes and analyzes sales and customer data effectively. This system should include pivot tables, dashboards, and visual reports to identify key customer demographics, sales trends, and product performance. By integrating data from multiple sources—such as customer profiles, purchase history, income levels, and device usage—the solution will provide actionable insights that help optimize marketing strategies, improve inventory management, and enhance overall business performance.

## User story

"As a Data Analyst, I want an Excel-based dashboard that integrates sales and customer data, allowing me to quickly identify key customer demographics, purchasing behaviors, and sales trends. I want to analyze product performance, track device usage for online orders, and assess quarterly sales to optimize marketing strategies, improve inventory management, and enhance business decision-making.

# Data source

- What data is needed to achieve our objective?

  We need data on the company, including their
  - Data
  - Order ID
  - Product Category
  - Product Sub-Category
  - Region
  - State
  - Customer source
  - Order Date
  - Ship Date
  - Shipping Method
  - Expense
  - QTY Sold
  - Unit Price
  - Sales Amount
  - Profit
  - Customer ID
  - First Name
  - Last Name
  - Address
  - City
  - Homeownership
  - Urban/Rural
  - Income
  - Tier
  - Device Used
 


# Design 

## Dashboard components required 
- What should the dashboard contain based on the requirements provided?

To understand what it should contain, we need to figure out what questions we need the dashboard to answer:

1. What is the homeownership status of customers (homeowner, renter, or disclosed) and and what is the average sales amount?
2. How can customers be classified into low, middle, or high-income tiers based on their income data?
3. Which product category—dog accessories, dog care, or organic dog food—has the highest sales?
4. What device (PC, tablet, or phone) is most commonly used for placing orders?
5. How do sales trends vary by year and quarterly performance?



## Tools 


| Tool | Purpose |
| --- | --- |
| Excel | Exploring the data | Data Cleaning | Pivot Tables | PowerPivot | Dashboards |
| GitHub | Hosting the project documentation and version control |


# Development

## Pseudocode

- What's the general approach in creating this solution from start to finish?

1. Get the data
2. Create a new column in the 'W Customer' sheet.
3. Call it Tier to use IFS statements, to find if their income is low, middle, or high class.
4. Go to Power Pivot and click on Data Model for both sheets 'W Customer' and 'W Order'.
5. Click on diagram view and connect the Customer: Customer ID and Order: Customer ID.
6. Create new sheets and call it 'Pivot Tables' and 'Dashboards'.
7. Click on Insert and click on Pivot Tables. Click on the data model.
8. Create Pivot Tables to find the answer to the questions.



## Data cleaning 
- What do we expect the clean data to look like? (What should it contain? What constraints should we apply to it?)

We aim to refine our dataset to ensure it is structured and ready for analysis. 

The cleaned data should meet the following criteria and constraints:

- Filling the empty cells.
- Creating a new column to find the customer's class level.

![IFS](assets/images/Excel_Data_Project.png)



# Analysis 

## Findings

- What did we find?

For this analysis, we're going to focus on the questions below to get the information we need for the Dog Superstore Sales & Customer Insights Analysis.

Here are the key questions we need to answer for the Dog Superstore Sales & Customer Insights Analysis.
1. What is the homeownership status of customers (homeowner, renter, or disclosed) and what is the average sales amount?
2. How can customers be classified into low, middle, or high-income tiers based on their income data?
3. Which product category—dog accessories, dog care, or organic dog food—has the highest sales?
4. What device (PC, tablet, or phone) is most commonly used for placing orders?
5. How do sales trends vary by year and quarterly performance?

### 1. What is the homeownership status of customers (homeowner, renter, or disclosed) and what is the average sales amount?

| Rank | Homeownership   | Average of Sales Amount |
|------|-----------------|-------------------------|
| 1    | Undisclosed     | $70.16                  |
| 2    | Rent            | $64.29                  |
| 3    | Own             | $62.96                  |

![IFS](assets/images/Excel_Data_Project.png)


### 2. How can customers be classified into low, middle, or high-income tiers based on their income data?

| Rank | Income          | Sum of Sales Amount     |
|------|-----------------|-------------------------|
| 1    | Middle          | $19,792                 |
| 2    | High            | $9,792                  |
| 3    | Low             | $5,929                  |

![IFS](assets/images/Excel_Data_Project.png)


### 3. Which product category—dog accessories, dog care, or organic dog food—has the highest sales?

| Rank | Product         | Sum of Sales Amount     |
|------|-----------------|-------------------------|
| 1    | Dog care        | $18,044                 |
| 2    | Dog Food Organic| $9,670                  |
| 3    | Dog Accessories | $7,181                  |

![IFS](assets/images/Excel_Data_Project.png)


### 4. What device (PC, tablet, or phone) is most commonly used for placing orders?

| Rank | Decive         | Sales Amount     |
|------|----------------|------------------|
| 1    | PC             | $17,861          |
| 2    | Phone          | $11,334          |
| 3    | Tablet         | $5,700           |

![IFS](assets/images/Excel_Data_Project.png)


### 5. How do sales trends vary by year and quarterly performance?

| Year | Quarterly    | Sum of Sales Amount    |
|------|--------------|------------------------|
| 2018                  $11,945                |
       | Qtr 1        | $2,531                 |
       | Qtr 2        | $3,219                 |
       | Qtr 3        | $2,936                 |
       | Qtr 4        | $3,259                 |
|------|--------------|------------------------|
| 2019                  $11,333                |
       | Qtr 1        | $3,136                 |
       | Qtr 2        | $2,488                 |
       | Qtr 3        | $2,724                 |
       | Qtr 4        | $2,985                 |
|------|--------------|------------------------|
| 2020                  $11,617                |
       | Qtr 1        | $2,744                 |
       | Qtr 2        | $2,872                 |
       | Qtr 3        | $3,025                 |
       | Qtr 4        | $2,976                 |

![IFS](assets/images/Excel_Data_Project.png)



# Conclusion


## What do you recommend based on the insights gathered?

### 1. Based on the homeownership status of customers and the average sales amount.

Target Undisclosed Customers – Encourage data sharing with incentives, as they have the highest average sales.
Focus on Renters – They spend more than homeowners, so tailor promotions to their needs.
Engage Homeowners More – Offer home-related deals and financing options to boost spending.
Use Personalized Marketing – Leverage customer data for targeted campaigns.


### 2. Based on customers be classified into low, middle, or high-income tiers based on their income data.

Prioritize Middle-Income Customers – They contribute the most to sales, so focus marketing and loyalty programs on them.
Re-engage High-Income Customers – Offer premium products, personalized services, or exclusive deals to increase their spending.
Support Low-Income Customers – Implement budget-friendly promotions or installment payment options to boost their sales.


### 3. Based on product category—dog accessories, dog care, or organic dog food—has the highest sales.

Invest in Dog Care Products – Since they generate the highest sales, expand offerings and promotions in this category.
Boost Organic Dog Food Sales – Highlight health benefits and introduce discounts or bundles to attract more buyers.
Increase Visibility of Dog Accessories – Use upselling strategies, bundling with dog care products, or targeted marketing.


### 4. Based on device (PC, tablet, or phone) is most commonly used for placing orders.

Optimize the PC Ordering Experience – Since PCs generate the highest sales, enhance the desktop website for better performance and user experience.
Improve Mobile Shopping – Invest in mobile app development and responsive design to boost phone sales.
Reevaluate Tablet Strategy – Consider targeted promotions or assess if maintaining tablet optimization is cost-effective.


### 5. Based on sales trends vary by year and quarterly performance. 

Stabilize Quarterly Sales – Sales fluctuate across quarters. Implement strategies like promotions or product launches in lower-performing quarters (e.g., Q2 in 2019).
Identify Growth Opportunities – While annual sales remain relatively stable, focus on driving higher growth through better marketing and customer engagement.
Leverage Seasonal Trends – Q4 often has stronger sales, suggesting holiday demand. Capitalize on this with targeted campaigns and inventory management.
