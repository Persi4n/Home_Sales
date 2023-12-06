# Home Sales Data Analysis with PySpark

## Overview

This project employs PySpark, a robust distributed computing framework, to conduct a comprehensive analysis of home sales data. The dataset utilized is sourced from the `home_sales_revised.csv` file, encompassing a detailed exploration of real estate trends.

## Project Structure

The project is organized into two main components:

1. **Home_Sales.ipynb:** This Jupyter notebook initiates the data processing and analysis using PySpark SQL. Key tasks encompass creating a Spark DataFrame, establishing a temporary table, executing Spark SQL queries, and exploring caching and uncaching strategies. 

2. **Home_Sales_starter_code_colab.ipynb:** This continuation notebook expands the analysis, incorporating additional tasks such as installing Spark in a Colab environment, loading data into a DataFrame, creating temporary tables, and running queries on Parquet-formatted data.

## Requirements

- PySpark
- Jupyter Notebooks
- Internet access to retrieve data from an AWS S3 bucket

## Analysis Summary

### 1. Data Exploration

The initial stages involve loading and exploring the home sales dataset. Key statistics and visualizations are employed to gain insights into the overall distribution of property values, bedroom configurations, and other pertinent factors.

### 2. Spark SQL Queries

Various Spark SQL queries are formulated to answer specific questions about the home sales data. This includes calculating average prices for different property configurations, exploring trends over time, and identifying high-value properties.

### 3. Performance Optimization

Caching strategies are employed to enhance query performance. The impact of caching on runtime is measured, providing valuable insights into the efficiency gains associated with in-memory data storage.

### 4. Parquet Data Analysis

The project extends its analysis to Parquet-formatted data, showcasing the versatility of PySpark in handling different data formats. Temporary tables are created, and Spark SQL queries are executed on the partitioned Parquet data.

## Instructions

1. **Environment Setup:**
   - Ensure PySpark is correctly installed in your environment.
   - Open and execute each cell in the provided Jupyter notebooks sequentially.

2. **Data Loading:**
   - The project fetches home sales data from an AWS S3 bucket. Internet access is required to download the dataset.

3. **Spark SQL Queries:**
   - Explore various Spark SQL queries designed to extract meaningful insights from the dataset.

4. **Caching and Uncaching:**
   - Observe the impact of caching on query performance and understand the process of uncaching for memory management.

5. **Parquet Data Analysis:**
   - Delve into the intricacies of Parquet-formatted data, including partitioning strategies and query execution.
