# Movies ETL
## Overview of the Project
We have been asked to refactor our modules code to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database. By doing this we'll have an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. 

## Project Deliverables

1. Deliverable 1: Write an ETL Function to Read Three Data Files
2. Deliverable 2: Extract and Transform the Wikipedia Data
3. Deliverable 3: Extract and Transform the Kaggle Data
4. Deliverable 4: Create the Movie Database

### Deliverable 1: Write an ETL Function to Read Three Data Files

1. An ETL function is written to read in the three data files. 
2. The function converts the Wikipedia JSON file to a Pandas DataFrame, and the DataFrame is displayed in the `ETL_function_test.ipynb file`.
3. The function converts the Kaggle metadata file to a Pandas DataFrame, and the DataFrame is displayed in the `ETL_function_test.ipynb file`.
4. The function converts the MovieLens ratings data file to a Pandas DataFrame, and the DataFrame is displayed in the `ETL_function_test.ipynb` file.

### Deliverable 2: Extract and Transform the Wikipedia Data

1. We have filtered out TV shows that are not needed. 
2. A Try-Except block is used to catch errors
3. Extract and transform data through the created function to keep columns with non-null values, convert datat to string values, use regex to match elements and clean specific columns
4. Convert the data to a Pandas DataFrame in the `ETL_clean_wiki_movies.ipynb` file.

### Deliverable 3: Extract and Transform the Kaggle Data

1. Extract and transform data through the created function to clean the data, merge dataframes, remove unnecessary columns, fill in missing data, filter and rename columns. 

### Deliverable 4: Create the Movie Database

1. Added a dataframe and CSV file to a Postgres SQL database. 
2. Show the length of time to add the CSV file to the SQL database



