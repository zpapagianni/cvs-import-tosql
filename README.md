# CSV File to Database Import Automation
A python script that automates CSV file imports to a postgres database.

credit:(nate@stratascratch.com)
___

## Description
Importing CSV files to a database is a common task needed for data science and analytics and it can be done completely with python using pandas dataframes, numpy, os library, and the posgres database wrapper psycopg2.

This script will automatically import CSV files to a postgres database.The CSV files can be placed in the same directory as the notebooks and the notebook will automatically clean the file names and column headers, create the database tables, and copy the files over to the database. The table names are the same names as the file names. However, all upper case characters are changed to lower case, spaces are converted to underscores, and all symbols are removed. 


