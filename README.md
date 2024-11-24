End-to-End Data Analytics Project

This repository contains an end-to-end data analytics project that utilizes Python and SQL to process and analyze data. The goal is to demonstrate the complete lifecycle of a data analytics workflow, from dataset acquisition to answering key business questions.
Project Overview
Steps:

    Dataset Acquisition
        Use the Kaggle API to programmatically download the dataset.

    Data Processing and Cleaning
        Use Pandas for cleaning and transforming the dataset to ensure data quality and consistency.

    Data Storage
        Load the cleaned data into SQL Server for efficient querying and analysis.

    Data Analysis
        Write SQL queries to answer interesting and business-critical questions based on the dataset.

Dataset

The dataset contains information about sales transactions and includes the following fields:

    product_id: Unique identifier for each product.
    sale_price: The price at which a product was sold.
    category and sub_category: Hierarchical categorization of the products.
    region: Geographic region where the order was placed.
    order_date: The date the order was made.

Questions Answered

The analysis answers some insightful questions, such as:

    What are the total sales per region?
    Which category and sub-category have the highest revenue?
    What are the top-selling products?
    How do sales trends vary over time?

Technologies Used

    Python: For data processing and integration.
        Libraries: pandas, numpy, sqlalchemy, os
    SQL Server: For data storage and analysis.
    Kaggle API: For dataset acquisition.

How to Run
Prerequisites:

    Install Python (3.x recommended).
    Set up SQL Server and configure a database.
    Install the required Python libraries using the following command:

    pip install pandas numpy sqlalchemy kaggle

Steps:

    Clone the repository:

git clone https://github.com/your-username/end-to-end-data-analytics.git
cd end-to-end-data-analytics

Configure the Kaggle API:

    Download your kaggle.json file from your Kaggle account.
    Place it in the appropriate location (~/.kaggle/ for Linux/MacOS or %USERPROFILE%\.kaggle\ for Windows).

Run the data processing script:

    python data_processing.py

    Load the cleaned data into SQL Server using the provided SQL script.

    Analyze the data by running the SQL queries in the analysis_queries.sql file.

Future Enhancements

    Automate the pipeline using Apache Airflow.
    Create interactive dashboards with Power BI or Tableau.
    Expand analysis to include predictive modeling with machine learning.
    
