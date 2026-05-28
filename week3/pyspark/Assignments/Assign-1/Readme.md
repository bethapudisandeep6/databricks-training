# PySpark DataFrame Operations Assignment

This project demonstrates basic PySpark DataFrame operations using employee data.

## Topics Covered

- Select
- Alias
- Filter / Where
- withColumnRenamed
- withColumn
- Type Casting
- Sort / OrderBy
- Limit

## Technologies Used

- Python
- PySpark
- Apache Spark

## Dataset Columns

- emp_id
- emp_name
- age
- city
- designation
- salary
- joining_date
- department

## Operations Performed

### SELECT
- Selecting specific columns
- Selecting multiple columns
- Selecting columns with conditions

### ALIAS
- Renaming columns temporarily using alias()

### FILTER / WHERE
- Filtering records using conditions
- Using AND, OR, BETWEEN, STARTSWITH, ENDSWITH

### WITHCOLUMNRENAMED
- Permanently renaming columns

### WITHCOLUMN
- Creating new calculated columns
- Using when(), concat_ws(), year(), substring()

### TYPECASTING
- Converting columns into different datatypes

### SORT / ORDERBY
- Sorting data in ascending and descending order

### LIMIT
- Displaying limited records

## Run the Project

```python
spark-submit assignment.py
