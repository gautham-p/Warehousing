# Warehousing

Extract and Load the dataset related to Kaggle Project in Postgresql using just Poject name as input.

Using Kaggle Python API, we get the datasets as csv files and then make staging tables using postgres COPY command using psycopg2 library.
