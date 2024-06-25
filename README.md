# Cricket Data Analytics with Snowflake

## Project Overview

This project demonstrates the development of an end-to-end data engineering pipeline using Snowflake. The objective is to understand and utilize various Snowflake features such as data modeling, maintenance, cost efficiency, and data loading, by working with a cricket data analytics dataset in the form of nested JSON data.

## Features

- **Data Source**: JSON data file containing cricket match details.
- **Data Storage**: internal stages.
- **Data Warehouse**: Snowflake for data processing and storage.
- **Layered Architecture**: 
  - Landing Layer
  - Raw Layer
  - Cleaning Layer
  - Consumption Layer
- **Data Modeling**: Construction of fact and dimension tables.

## Technologies Used

- Snowflake Free Trial Account
- VSCode for text editing
- JSON File Visualizer
- Snowsight worksheets and SQL for data cleaning and transformations
- Snowsight WebUI for data loading
- Snowsight Dashboard for visualization

## Installation Instructions

1. **Create Snowflake Account**: Sign up for a Snowflake free trial account.
2. **Set Up Database and Schemas**: Set up your Snowflake database with schemas for different layers: land, raw, clean, consume.
3. **Create File Format and Stage**: Define a JSON file format and create a stage to load the JSON data file.
4. **Load JSON Data to Stage**: Load your JSON data into the stage using Snowsight WebUI for small datasets or SnowSQL CLI for bulk data loading.

## Usage Instructions

1. **Load Data from Landing to Raw Layer**: Transfer data from the landing stage to the raw layer.
2. **Transform Data in Raw Layer**: Flatten the nested data and convert semi-structured data to structured format.
3. **Clean Data in Clean Layer**: Extract fields as separate columns and perform data cleaning operations.
4. **Model Data in Consumption Layer**: Create fact and dimension tables to derive meaningful insights from the data.

## Development Steps

1. **Database and Schemas Setup**:
    - Created a database with schemas for landing, raw, clean, and consume layers.
2. **Data Loading**:
    - Defined JSON file format and stage in Snowflake.
    - Loaded data from local JSON files to the Snowflake stage.
3. **Data Transformation**:
    - Transformed and flattened data in the raw layer using Snowflake SQL functions.
    - Stored data in transient tables for temporary storage.
4. **Data Cleaning**:
    - Extracted and cleaned data in the clean layer.
    - Created new columns and tables as needed.
5. **Data Modeling**:
    - Constructed fact and dimension tables in the consumption layer.
    - Modeled tables to derive meaningful insights.



