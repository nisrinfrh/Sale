# Sale

### Introduction

As a data analyst, you play a vital role in analyzing large datasets to gain insights and improve business operations.

Microsoft Power Query is an essential tool in your workflow, allowing you to transform and integrate data from various sources.

At this point, you should have a good understanding of the best practices when using Microsoft Power Query and its practical applications. 

You gained valuable knowledge on planning, documentation, connectors, data profiling, performance, 

error handling, using groups, and optimizing data types. In this step-by-step exercise, you have the opportunity to apply best practices when importing datasets in Power BI.

### Busnes Tsak

Adventure Works is afictional company   which sells various consumer products. As the business expands,

the management team wants to gain deeper insights into their sales performance across different regions. You use Power BI to import and analyze the sales data.

The company uses CSV files containing the Adventure Works company sales, reseller ,region and product data. 

### PREPARE DATA

Step 1: Download the CSV files

Download the Sales.csv, Product.csv ,Date.CSV and Reseller.csv  files,

These files are available at THES REPSOTRY.

**Transform and clean data**

Remove duplicate from *SalesOrderNumber* columns in  Sales Table .
Prosses Data
**Modling data**
**Add New Column**
 usig powerqury editor in power bi We will Creat new columns 
  *Yearly sales by colour*  = ADDCOLUMNS(Sales,"Year",RELATED('Date'[Year]))
  

Step 5: Profile data
Examine the data in distribution, quality and profile. 

Find error and empty rows, calculate minimum, maximum, average, count and other statistics, and compare distinct and unique values in different sales columns.

Find the minimum, maximum, and average values of the UnitPrice column

Find distinct and unique values in the Product Name column. Compare the distinct and unique values and find the reason for that.

Find the Count value of the SalesOrderID column.

Write down the values that you found.

Conclusion
By following these best practices, you successfully import Adventure Works sales data into Power BI, enabling you to analyze and profile sales performance across different regions. You gain best practices for optimizing data extraction, transforming, cleansing, and profiling data.




The task
Your manager, Adio Quinn, asks you to conduct a detailed analysis of store sales. In the detail table, OrderDetails, there are multiple fields, but you only need ProductID, the quantity sold (which is in the field OrderQty), and the UnitPrice. Therefore, you are expected to remove unnecessary fields, and also eliminate empty rows, and identify any anomalies to remove those rows if necessary. After performing these tasks, you will append the two separate sales data sources together and then merge that with OrderDetails. Follow the steps below to complete the exercise.


**************************************************************************
Case study
Adventure Works needs your help to analyze its sales data and create a Power BI report that visualizes this data in a meaningful way. Before the analysis can begin, the raw data must be cleaned and transformed to make sure it's accurate and consistent.

The company sends you the CSV file containing the raw dataset named SalesFile.csv. The dataset consists of important data related to recent sales, such as product categories, manufacturing prices, sales prices, units sold, and other similar details.

However, the file also contains errors like missing values, incorrect data types, and inconsistent formatting. Help Adventure Works to resolve these issues using Power Query editor so that they can produce an accurate and reliable report.

This exercise aims to assist you in understanding how to address common data issues such as missing values, incorrect data types, and inconsistent formatting.

By the end of this exercise, you’ll understand how to import, clean, and transform data in Power BI Desktop to ensure accurate and reliable analysis.

Instructions
Create a new Power BI project called Exercise – Preparing a dataset. Follow the prompts below to complete the exercise.

Step 1: Load the workbook
Download the Microsoft Excel workbook SalesFile.xlsx.

Import the SalesFile.xlsx Excel file as your dataset in Power BI.

Step 2: Open the Power Query Editor
Open the Power Query editor to begin editing your data.

Step 3: Address missing values
Locate and select the Units Sold column. 

Identify all null values within the column and replace them with a value of 0. 


Transform
In Power BI Desktop, the Power Query Editor provides a range of capabilities for refining your imported data. You have the flexibility to perform tasks like modifying column or table names, converting text to numeric values, eliminating specific rows, designating the first row as headers, and many other operations. Shaping your data is crucial to tailor it to your requirements and make it suitable for reporting purposes.

Cleaning data gives you the following benefits:

Tables are well organized, where users can find the data easily.

Duplicates are removed.



A complicated column can be split into two, simpler columns.

Multiple columns can be combined into one column for readability.

Codes and integers can be replaced with human-readable values.

