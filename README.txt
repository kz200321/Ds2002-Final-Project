--------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Final Project Documentation
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Setup
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------
- Used Microsfot Azure remote server desktop to complete this project
- Data downloaded from datedo.com (Chinook database)
- Run Chinook SQL query to create database and tables also load data
- Setup MySQL azure, MongoDB, and DBFS with source_files folder
- Download fact table created from Midterm using python
- Download dimension tables using python
- Load all JSON/CSV files into database and file system
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Methods
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------
For the capstone project, I built my solution based off of the Chinook database used in the midterm project. After creating the fact tables in the midterm, I downloaded the table data into 3 JSON files along with the dimension tables. Using MongoDB, DBFS, and MySQL database, I imported 4 dimension tables: date, customer, artist, and invoice_line created from the midterm project. After loading them, I used streaming, hot path, to create the bronze, silver and gold aggregation tables. 