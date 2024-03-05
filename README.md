# Data_Cleaning_SQL
Nashville Housing Dataset Exploration
This repository contains a SQL file for data exploration and cleaning of the Nashville Housing dataset. The SQL queries perform various data analysis tasks such as filtering, aggregation, joining tables, and data cleaning.

Dataset
The dataset used in these queries is stored in the Sql_PortfolioProject database and includes the Nashville_housing_dataset table. The Nashville_housing_dataset table contains information about property sales in Nashville.

Queries
The SQL file includes several queries that perform different types of data analysis and cleaning:

Data Exploration: The first query selects all records from the Nashville_housing_dataset table.
Date Normalization: The second and third queries convert the SaleDate column to a standard date format.
Address Standardization: The fourth to seventh queries standardize the Property Address column by filling NULL values and splitting the address into different parts (house number, street name, and street type).
Sold As Vacant Standardization: The eighth and ninth queries standardize the Sold As Vacant column by replacing ‘Yes’ with ‘Y’ and ‘No’ with ‘N’.
Row Number Calculation: The last query calculates the row number for each record based on several columns.
Usage
To use these queries, you need to have access to the Sql_PortfolioProject database and the Nashville_housing_dataset table. You can run these queries in any SQL client or database management tool that supports SQL.

Please note that these queries are for data exploration and cleaning purposes and the results may vary depending on the data in your table.
