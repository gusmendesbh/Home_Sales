# Home_Sales
Module 22 Challenge

In this challenge, I used my knowledge of SparkSQL to determine key metrics about home sales data. Then you'll use Spark to create temporary views, partition the data, cache and uncache a temporary table, and verify that the table has been uncached.

## Key Takeaways:
Running a simple SQL query, and comparing results to cached and parquet data proved the efficiency of both methods over simple SQL.

Query:

![image](https://github.com/gusmendesbh/Home_Sales/assets/94866814/b307287b-acb3-4308-88d3-9d9140d4b831)

### 1 - Unchached Data: 
 ![image](https://github.com/gusmendesbh/Home_Sales/assets/94866814/aac31069-bee5-4433-9400-ca45fb265f8e)
 - 1.54s run time

### 2 - Cached Data:
![image](https://github.com/gusmendesbh/Home_Sales/assets/94866814/eec2e637-65e2-4631-aabf-12b8af8d80e2)
- 0.45s run time

### 3 - Parquet DataFrame
![image](https://github.com/gusmendesbh/Home_Sales/assets/94866814/6760561f-bde5-40f6-85e2-dbe2ad75d35e)
- 0.37 run time
