# Spark RDD vs DataFrame Performance Analysis

## Author

Rihem Belgacem

## Project Description

This project compares the performance of Apache Spark RDDs and DataFrames using the Online Retail dataset.

The objective is to evaluate the efficiency of both Spark abstractions when performing common big data analytics tasks such as aggregation, grouping, and sorting.

Two experiments were conducted:

1. Top Countries by Number of Transactions
2. Top Products by Quantity Sold

Execution times were measured and compared for both implementations.

## Technologies Used

- Apache Spark
- PySpark
- Google Colab
- Python

## Dataset

The project uses the Online Retail dataset.

File included in this repository:

- online_retail.zip

## Running the Project

1. Open the notebook in Google Colab.
2. Upload and extract the dataset if necessary.
3. Execute all notebook cells in order.
4. Review the results and execution time comparisons.

## Repository Contents

- spark_rdd_vs_dataframe.ipynb : Main notebook
- online_retail.zip : Dataset
- README.md : Project documentation

## Results

The experiments show that Spark DataFrames consistently outperform Spark RDDs while producing identical analytical results.

## License

Academic project developed for the Big Data Analytics course.
# spark-rdd-vs-dataframe-analysis
Performance comparison between Apache Spark RDDs and DataFrames using the Online Retail dataset.
