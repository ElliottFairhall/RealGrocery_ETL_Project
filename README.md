
# RealGrocery - ETL, Data Warehouse, and Data Mart Design Project

![alt text](/assets/RealGroceryCompany.jpg)

**Please note that RealGrocery is a fictitious company and this project is part of my personal collection of projects.**

## Overview

The goal of this project is to design and implement an Extract, Transform, Load (ETL) process, a data warehouse, and a data mart for RealGrocery, a Canadian-based retail business. The project will leverage the extensive dataset of product information scraped from the Real Canadian Superstore website. The data, currently stored in JSON extracts, will be cleaned, transformed, and loaded into a data warehouse (Snowflake). This transformation will enable more efficient data analysis and business intelligence operations.

## Technical Requirements

The project encompasses the following key technical requirements:

-   **ETL Process Design:**  Develop an ETL process to extract data from JSON files, transform it to meet the business requirements and load it into Snowflake.
    
-   **Data Warehouse Design:**  Design a robust and scalable data warehouse in Snowflake to accommodate the transformed data.
    
-   **Data Mart Design:**  Develop a data mart to effectively utilize the data stored in Snowflake for generating insights and informing business decisions.
    
-   **Data Cleaning and Transformation:**  The dataset will undergo data cleaning and transformation to ensure data consistency, accuracy, and compliance with Snowflake’s requirements.
    
-   **Data Loading into Snowflake:**  The cleaned data will be loaded into Snowflake, a cloud-based data warehousing platform, using SQL-based operations.
    
-   **Stored Procedures and Functions:**  Stored procedures and functions will be developed to automate common data processing tasks, improving data quality and efficiency.
    
-   **Scheduled Tasks:**  Tasks will be scheduled for regular data updates and maintenance to ensure the dataset remains up-to-date.
    
-   **Data Diagrams:**  Visual representations, such as ER diagrams, will be created to illustrate the database schema and relationships, facilitating a better understanding of the data structure.
    

## Minimum Viable Product (MVP)

The MVP for this project should include:

-   A fully functional ETL process that can extract data from JSON files, transform it according to business requirements, and load it into Snowflake.
-   A robust and scalable data warehouse in Snowflake that can accommodate the transformed data.
-   A well-designed data mart that can effectively utilize the data stored in Snowflake for generating insights and informing business decisions.
-   A set of stored procedures and functions for automating common data processing tasks.
-   A schedule for regular data updates and maintenance tasks.
-   A set of ER diagrams or other visual representations of the database schema and relationships.

## Getting Started

The following steps outline what steps are required to meet the MVP:

1.  **ETL Process Design:**  Use Python scripts to design an ETL process that can extract data from JSON files, transform it according to business requirements, and load it into Snowflake.
2.  **Data Warehouse Design:**  Design a robust and scalable data warehouse in Snowflake that can accommodate the transformed data.
3.  **Data Mart Design:**  Develop a well-designed data mart that can effectively utilize the data stored in Snowflake for generating insights and informing business decisions.
4.  **Stored Procedures and Functions:**  Develop stored procedures and functions using SQL scripts to automate common data processing tasks.
5.  **Scheduled Tasks:**  Schedule regular tasks for updating the dataset using SQL scripts.
6.  **Data Diagrams:**  Use a data modeling tool to create ER diagrams or other visual representations of the database schema and relationships.

## References

This project is based on the dataset from Kaggle: [Real Canadian Superstore Grocery Data]. The dataset was created by Maxim Sakhan, a data analyst and enthusiast. The dataset contains product information scraped from the Real Canadian Superstore website. The dataset was last updated on July 6, 2021.

: https://www.kaggle.com/datasets/maximsakhan/rc-superstore-grocery-data/?select=products_raw_data.csv
