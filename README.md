Overview:
=========
This repository contains a python script designed to perform data cleaning and transformation on a customer dataset. The script is intended for data engineers to practice essential skills in the data manipulation, preprocessing, and preparing data for analysis or database loading.

Dataset:
========
The dataset provided is a csv file named customer_data.csv, containing customer information with columns that include:
* Customer ID
* Name
* Email
* DateOfBirth
* RegistrationDate
* Country
* MonthlySpend

Customer Data:
==============
CustomerID,Name,Email,DateOfBirth,RegistrationDate,Country,MonthlySpend
1,John Doe,johndoe@example.com,2/15/1985,2024-01-12,United States,200
2,Jane Smith,janesmith@example.com,8/20/1990,,United States ,300
3,Alan Brown,alanbrown@example.com,1/15/1975,2024-02-05, Canada,150
4,Eva White,evawhite@example.com,7/30/1987,2024-02-15,united states,400
5,Mark Black,markblack@example.com,2/12/1982,2024-02-15,Canada,
6,Lisa Green,lisagreen@example.com,10/19/1979,2024-04-10,United Kingdom,250
7,Paul Blue,paulblue@example.com,11/3/1983,2024-01-28,united kingdom,
8,Alice Pink,alicepink@example.com,4/22/1977,2024-05-18, Mexico,450
9,Mary Orange,maryorange@example.com,,2024-02-22,France,300
10,Chris Gray,chrisgray@example.com,12/11/1986,2024-03-01, United States,

Task Objectives:
================
1. Data Cleaning:
                * Handling missing values in RegistrationDate and MonthlySpend
                * Standardize DateOfBirth to YYYY-MM-DD format.
                * Clean Country to have consistent capitalization and remove leading/trailing spaces.
                * Remove duplicate entities based on CustomerID ( If any).
2. Data Transformation:
                * Create a new column 'Age' derived from DateOfBirth.
3. Output:
         * Save the cleaned and transformed data to a new csv file named cleaned_customer_data.csv.

Requirement:
============
1. Python 3.x
2. Pandas library

Contributing:
=============
Feel free to submit issues or pull requests if you have improvements or corrections.











