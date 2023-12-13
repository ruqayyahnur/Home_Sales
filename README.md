##### Home_Sales
module 22

# Overview
This challenge focus on the usage of SparkSQL to determine key metrics about home sales data. Spark will be used to create temporary views, parition the data , cache and unchace a temporary table, and verify the table has been uncached. 

# Process
###  - Answer the following questions using SparkSQL:
          - What is the average price for a four-bedroom house sold for each year? Round off your answer to two decimal places.
          - What is the average price of a home for each year it was built that has three bedrooms and three bathrooms? Round off your answer to two decimal places.
          - What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet? Round off your answer to two decimal places.
          - What is the "view" rating for homes costing more than or equal to $350,000? Determine the run time for this query, and round off your answer to two decimal places.
### - Check if your temporary table is cached.
### - Using the cached data, run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
### - Run the query that filters out the view ratings with an average price of greater than or equal to $350,000. Determine the runtime and compare it to uncached runtime.
### - Uncache the home_sales temporary table.
### - Verify that the home_sales temporary table is uncached using PySpark.
