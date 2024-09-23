# Home_Sales
Homework for Module 22


This challenge requires the use of SparkSQL to identify important metrics related to home sales data. Spark was employed to establish temporary views, partition the dataset, cache and uncache a temporary table, and confirm that the table has been successfully uncached.



This challenge consists of the following steps:

A Spark DataFrame is created from the dataset.

A temporary table is generated from the original DataFrame.

A query is crafted to return the average price, rounded to two decimal places, for four-bedroom homes sold each year.

A query is developed to return the average price, rounded to two decimal places, of homes with three bedrooms and three bathrooms for each year they were built.

A query is constructed to return the average price, rounded to two decimal places, of homes featuring three bedrooms, three bathrooms, two floors, and a minimum of 2,000 square feet, for each year they were built.

A query is formulated to return the average price per view rating, where the average home price is at least $350,000, rounded to two decimal places. (The output includes the runtime for this query.)

A cache of the temporary home_sales table is created and confirmed.

The query from step 6 is executed on the cached temporary table, and the runtime is recorded.

The home sales dataset is partitioned by the date_built field, and the formatted parquet data is read.

A temporary table is created from the parquet data.

The query from step 6 is executed on the parquet temporary table, and the runtime is recorded.

The home_sales temporary table is uncached and verified.


Files of repository
Home_Sales_colab.ipynb: the file contains all analysis, using Google colab.

