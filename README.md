# Movies-ETL

## Purpose

We are tasked to refactor our previous code to create a Movie Database with clean Wiki and Kaggle data. In our refactored code, we created one large function that loaded our three data files, cleaned the data and then imported to our Postgres Database.

## Overview

- Read all three files into Pandas Dataframe in ETL_function_test.ipynb.

- Clean and transform Wiki data in ETL_clean_wiki_movie.ipynb.

- Clean and transform Kaggle date in ETL_clean_kaggle_data.ipynb.

- Combine all previous steps and import clean data into Postgres in to one function in ETL_clean_kaggle_data.ipynb.

## Summary

In summary, our refactored code can now be used to extract, clean and load any movie data from Wiki and Kaggle as long as the csv file and paths are updated.
