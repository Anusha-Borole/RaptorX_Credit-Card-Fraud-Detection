This project demonstrates bulk file handling, conversion, and SQL querying on the Credit Card Fraud Detection dataset using Apache Spark with Python (PySpark).
Project Overview
The project performs the following tasks:
Data Acquisition: Downloads the Credit Card Fraud Detection dataset from Kaggle.
Bulk File Handling: Loads multiple CSV files into a single Spark DataFrame.
Data Exploration: Performs exploratory data analysis, including:
Checking the dataset shape
Identifying null or missing values
Calculating descriptive statistics
Data Cleaning: Prepares the dataset for ETL processing by:
Handling missing values
Renaming columns for consistency
Data Transformation: Creates a new column "NormalizedAmount" containing normalized values of the "Amount" column.
Mathematical Transformation: Adds a new column "AmountLog" with the natural logarithm of the "Amount" column plus one.
File Conversion: Converts the cleaned and transformed DataFrame to Parquet format.
SQL Querying: Registers the DataFrame as a temporary SQL view and performs queries to answer specific questions.
Key Features
Utilizes PySpark for efficient big data processing
Demonstrates data cleaning and transformation techniques
Showcases SQL querying capabilities within a Spark environment
