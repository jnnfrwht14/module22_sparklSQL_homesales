# module22_sparklSQL_homesales - Big Data

## I used PySpark & SparkSQL on Google Colab to review the home sales data. I created temporary views, partitioned the data & cached/uncached a temporary table. The following questions were answered.

* What is the average price for a four-bedroom house sold for each year?

 ![Screenshot 2024-03-13 102542](https://github.com/jnnfrwht14/module22_sparklSQL_homesales/assets/144621532/bde3d70d-9005-4099-9af8-6d5d0a6b206c)

* What is the average price of a home for each year it was built that has three bedrooms and three bathrooms?

![Screenshot 2024-03-13 102733](https://github.com/jnnfrwht14/module22_sparklSQL_homesales/assets/144621532/c12f59e5-9f86-4169-ad4a-4e5281e76d04)

* What is the average price of a home for each year that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet?

![Screenshot 2024-03-13 102805](https://github.com/jnnfrwht14/module22_sparklSQL_homesales/assets/144621532/86ca0d42-43f8-4f5c-a485-bcbcf83529d7)

* What is the "view" rating for homes costing more than or equal to $350,000?

![image](https://github.com/jnnfrwht14/module22_sparklSQL_homesales/assets/144621532/ae43ed49-4cd4-4c04-bb0c-d723c1900aca)

## References

https://spark.apache.org/docs/latest/sql-ref-syntax-aux-cache-uncache-table.html
https://spark.apache.org/docs/2.1.0/api/python/pyspark.sql.html#pyspark.sql.DataFrame.orderBy
