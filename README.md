README
Overview
This project involves analyzing home sales data using SparkSQL to determine key metrics. The dataset includes information on price, year built, bedrooms, bathrooms, floors, square footage, livable square footage, and more. The challenge consists of using Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

Steps
Data Loading: Load the home sales data into a Spark DataFrame.
Temporary View Creation: Create temporary views of the DataFrame for SQL queries.
Query Execution: Execute various SQL queries to determine key metrics about home sales.
Caching: Cache the temporary table to improve query performance.
Partitioning: Partition the data by the date_built field and save it in Parquet format.
Uncaching: Uncache the temporary table to free up memory.
Verification: Verify that the table has been successfully uncached.
