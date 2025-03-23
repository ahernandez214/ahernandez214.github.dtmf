# Excel Data Project


![excel-data-project](assets/images/Excel_Data_Project.png)




# Table of contents

- [Objective](#objective)
- [Data Source](#data-source)
- [Design](#design)
  - [Tools](#tools)
- [Development](#development)
  - [Pseudocode](#pseudocode)

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

1. What is the homeownership status of customers (homeowner, renter, or disclosed)?
2. What is the average and total sales amount, and how do they reflect revenue trends?
3. How can customers be classified into low, middle, or high-income tiers based on their income data?
4. Which product category—dog accessories, dog care, or organic dog food—has the highest sales?
5. What device (PC, tablet, or phone) is most commonly used for placing orders?
6. How do sales trends vary by year and quarterly performance?



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
