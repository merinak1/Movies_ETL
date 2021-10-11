#  Movies ETL
Module 8 Challenge

The purpose of the Movies ETL is to update data on a daily basis. The function called Extract_Load_Transform is created. The Extract_Load_Transform function takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process and uploaded the data to a PostgreSQL database. 

1) **ETL_function_test.ipynb** - Test function to read the data from Wikipedia, Kaggle and Movie lens and adds into appropriate Pandas dataframe.

2) **ETL_clean_wiki_movies.ipynb** - Cleans and transforms the wikipedia data 

3) **ETL_clean_kaggle_data.ipynb** - Cleans and transforms the kaggle and ratings data 

4) **ETL_create_database.ipynb** - Loads the data into Postgres database into movies and ratings tables 