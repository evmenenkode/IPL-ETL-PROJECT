# IPL Data Analysis and ETL Pipeline
## Overview
This project involves building an ETL pipeline and performing data analysis on IPL (Indian Premier League) data. The project utilizes AWS S3 for data storage and Databricks for data processing and analysis. The primary goal is to clean the data, perform transformations, and conduct various analyses to extract insights from the IPL datasets.

## Datasets
The project uses the following datasets:

- Ball_By_Ball.csv: Contains ball-by-ball information for each match.
- Match.csv: Contains details of each match.
- Player.csv: Contains details of each player.
- Player_match.csv: Contains player performance data for each match.
- Team.csv: Contains team details.
  
## Project Structure
### ETL Pipeline

The ETL pipeline involves the following steps:

- Data Ingestion: Loading data from AWS S3 into Databricks.
- Data Cleaning: Handling missing values, normalizing data, and filtering records.
- Data Transformation: Creating new columns, aggregating data, and applying window functions.
- Data Analysis: Running SQL queries and generating visualizations to extract insights.

## Technologies Used
- AWS S3: For data storage.
- Databricks: For data processing and analysis using Apache Spark.
- PySpark: For data processing.
- Matplotlib and Seaborn: For data visualization.
