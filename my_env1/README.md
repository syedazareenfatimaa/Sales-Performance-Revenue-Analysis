# Walmart Data Analysis: End-to-End SQL + Python Project
## Project Overview
This project is an end-to-end data analysis solution designed to extract critical business insights from Walmart sales data. I used Python for data processing and analysis, SQL for advanced querying, and structured problem-solving techniques to solve key business questions. 

## Tools & Technologies
**SQL** – For querying, aggregating, and analyzing structured sales data  
**Python** – Using Pandas and Matplotlib for data analysis and visualization  
**Visual Studio Code** – For documenting the workflow, organizing code and project files

## Key Analyses
- Total revenue by **product** and **region**  
- Monthly and yearly **sales trends**  
- Identification of **top-performing products**  
- Revenue contribution analysis per product/region  

## Installed Required Libraries and Load Data
- Libraries: Installed necessary Python libraries using:
    pip install pandas numpy sqlalchemy mysql-connector-python psycopg2
- Loading Data: Read the data into a Pandas DataFrame for initial analysis and transformations.

## Explore the Data
Goal: Conduct an initial data exploration to understand data distribution, check column names, types, and identify potential issues.
Analysis: Use functions like .info(), .describe(), and .head() to get a quick overview of the data structure and statistics.

## Data Cleaning
- Remove Duplicates: Identified and removed duplicate entries to avoid skewed results.
- Handled Missing Values: Dropped rows or columns with missing values if they are insignificant; fill values where essential.
- Fixed Data Types: Ensured all columns have consistent data types (e.g., dates as datetime, prices as float).
- Currency Formatting: Used .replace() to handle and format currency values for analysis.
- Validation: Checked for any remaining inconsistencies and verify the cleaned data.

## Feature Engineering
- Created New Columns: Calculated the Total Amount for each transaction by multiplying unit_price by quantity and adding this as a new column.
- Enhanced Dataset: Adding this calculated field will streamline further SQL analysis and aggregation tasks.

## Load Data into MySQL
- Set Up Connections: Connect to MySQL using sqlalchemy and load the cleaned data into each database.
- Table Creation: Set up tables in both MySQL using Python SQLAlchemy to automate table creation and data insertion.
- Verification: Ran initial SQL queries to confirm that the data has been loaded accurately.

## SQL Analysis: Complex Queries and Business Problem Solving
- Business Problem-Solving: Wrotes and execute complex SQL queries to answer critical business questions, such as:
Revenue trends across branches and categories.
Identifying best-selling product categories.
Sales performance by time, city, and payment method.
Analyzing peak sales periods and customer buying patterns.
Profit margin analysis by branch and category.
