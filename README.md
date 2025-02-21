# Crime Data Analysis Using Hive and Python

## Overview
This project focuses on analyzing crime data using Apache Hive for efficient querying and Python for preprocessing and visualization. We leverage the power of MapReduce to process large datasets quickly, enabling deep-dive analysis and valuable insights.

## Dataset
The crime datasets used in this analysis were sourced from [DataKC - City of Kansas City, MO](https://www.kcmo.gov/city-hall/departments/city-manager-s-office/datakc). We specifically downloaded datasets from 2020 to 2024 for analysis.

## Data Preprocessing
Before analyzing the data, we performed various preprocessing steps using Python:
- Handling duplicate values
- Standardizing formats
- Cleaning and structuring data
- Merging all datasets into a single large file for Hive processing

## Data Analysis Using Hive
Hive is used for faster querying and deeper analysis. Some key operations performed include:
- Querying and filtering data based on crime type, location, and time
- Aggregating crime trends over time
- Identifying high-crime areas
- Performing joins and complex queries for insight generation

## Data Visualization
Python is used for visualization to better understand crime trends and patterns. Some visualization techniques applied:
- Time-series analysis of crime occurrences
- Heatmaps for high-crime areas
- Bar charts and histograms for crime type distributions

## Technologies Used
- **Apache Hive**: Efficiently processes large datasets using SQL-like queries.
- **Python**: Used for preprocessing, cleaning, and visualization.
- **MapReduce**: Enhances the speed of Hive queries.
- **Pandas & Matplotlib**: Used for data handling and visualization.

## What we did
1. Download the datasets from [DataKC](https://www.kcmo.gov/city-hall/departments/city-manager-s-office/datakc).
2. Run the Python scripts for data preprocessing.
3. Load the processed dataset into Hive.
4. Execute Hive queries to analyze the data.
5. Use Python for visualization based on analysis results.

## Conclusion
This project demonstrates how large-scale crime data can be efficiently processed using Hive and Python. By leveraging Hive’s querying power and Python’s visualization capabilities, we gain deep insights into crime trends and patterns, aiding in informed decision-making.


