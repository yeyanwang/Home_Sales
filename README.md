# Home_Sales

## Project Description
In this project, SparkSQL was employed to determine key metrics about home sales data. The utilization of SparkSQL involved various operations such as creating temporary views, partitioning the data, caching and uncaching a temporary table, and verifying that the table has been uncached.

## Analysis
**Query 1:** Average price for a four-bedroom house sold for each year

  ![image](https://github.com/yeyanwang/Home_Sales/assets/120543690/db7e63f2-d41a-4486-9049-e6bc76592374)

**Query 2:** Average price of a home for each year it was built that has three bedrooms and three bathrooms 
 
  ![image](https://github.com/yeyanwang/Home_Sales/assets/120543690/5ee38842-b224-4f77-bf0b-6d536b3c182f)

**Query 3:** Average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet

  ![image](https://github.com/yeyanwang/Home_Sales/assets/120543690/0a347f4a-7289-432e-9f58-67df61311fe7)

**Query 4:** View rating for homes costing more than or equal to $350,000 group by view
 
  ![image](https://github.com/yeyanwang/Home_Sales/assets/120543690/815c6685-8dd1-42cc-84bf-23716c81f42f)

**Compare Run Times on Query 4**
1. Uncache Runtime: 1.170952320098877 seconds
2. Cached Runtime: 0.705822229385376 seconds
3. Runtime with the parquet DataFrame: 0.8171482086181641 seconds

## Data
Visit "https://2u-data-curriculum-team.s3.amazonaws.com/dataviz-classroom/v1.2/22-big-data/home_sales_revised.csv" to download the home sale dataset used in this project. 

