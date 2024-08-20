# DataSpark-Illuminating-Insights-for-Global-Electronics

Project Overview:

This project involves a comprehensive process of cleaning, merging, and analyzing Customer data, Sales data, Exchange rate data and the Store data. 
       

Below is a detailed step-by-step guide of the workflow followed:

Step 1: Collecting all the files Create folder with all the csv files to run the python file in the same folder 

Step 2: Data Cleaning Reading the Data: Utilized Python and Pandas to read the CSV files for customers, sales, exchange rates, and stores. Handling Missing Values: Identified and filled null values using appropriate methods. Data Type Conversion: Converted columns to their respective data types (e.g., Dates, Integers, Floats).

Step 3: Data Merging Merging Datasets: Merged all cleaned data into a single DataFrame using the Pandas merge function with the inner join method.

Step 4: Uploading Data to SQL Connecting to SQL Database: Established a connection to the SQL database using SQLAlchemy. Pushing Data to SQL: Pushed the cleaned and merged DataFrame to the SQL database named project_2.

Step 5: Data Analysis with SQL Writing SQL Queries: Created SQL queries to analyze customer, sales, product, and store data.

Step 6: Data Visualization with Power BI Uploading Queries: Uploaded the results of each SQL query into Power BI. Creating Visualizations: Created visualizations to present insights from the data analysis.
