# Assessment 2
Prerequisits: Jyputer notebook, latest version of Apache Spark, Pyspark libraries

In this project, you will understand a few basic Python operations on a dataframe.

Download a sample JSON file, containing the reviews and ratings of a few locations.

Operations demonstrated in the code file:

1. Loading the file to the Jyputer notebook using the spark.read operation and convert it to a dataframe. The CreateOrReplaceTempView()()unction creates a table name that can be used in spark-sql queries.

2. A spark-sql query to convert the epoch time to date string with mm-dd-yyyy format

3. Create a table in postgre to load the dataframe. Use the following code to write the data to postgre server

4. Writing the dataframe to parquet file
