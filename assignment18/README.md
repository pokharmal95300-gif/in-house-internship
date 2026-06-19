# Assignment 18 - PySpark Partition Management

## Objective
Create a PySpark DataFrame with 5 million records and demonstrate partition management.

## Tasks Performed
- Generated a DataFrame containing 5 million records using spark.range().
- Displayed the initial number of partitions.
- Increased partitions to 12 using repartition().
- Reduced partitions to 3 using coalesce().
- Verified partition counts after each operation.

## Technologies Used
- Python
- PySpark
- Apache Spark
- Docker
- Java
- Jupyter Notebook

## Files
- assignment18.ipynb
- Dockerfile
- README.md

## Output
Initial Partitions: Depends on Spark configuration

Partitions After Repartition: 12

Partitions After Coalesce: 3