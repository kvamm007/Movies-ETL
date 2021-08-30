# Movies-ETL

The purpose of this project was to download, clean, and combine data from Wikipedia, Kaggle & MovieLens to get a complete picture of movies including basics (run time, title, budget, box office, etc) as well as ratings associated with the movies, for Amazing Prime. 

## Included files:

1. ETL_function_test.ipynb is the initial file created to test & validate the original portion of the function to read in the files. 
2. ETL_clean_wiki_movies contains all of the information in 1, plus additional functionality to clean the Wiki data source
3. ETL_clean_kaggle_data.ipynb contains all of the information in 2 (including information from 1) plus additional functionality to clean the Kaggle data source along with the Wiki data source, and merge the two sources together into one table including the movie info & ratings info.
4. ETL_create_database file contains all information from 3 (including info from 1 & 2- cumulative contains all info in all previous files) plus an additional step to link the program to clean & merge the files into a SQL database via PostGreSQL which we will be able to query to analyze additional information about the movies. 

Movies query:
![movies_query](https://user-images.githubusercontent.com/85597801/131273587-ac022ae1-f0ad-4b93-a1f7-77b023bda983.png)


Ratings query:
![ratings_query](https://user-images.githubusercontent.com/85597801/131273600-5b97f917-f5c7-4e3b-a2d4-2717bb5d167f.png)


Elapsed time to run import into SQL:
![Time Elapsed](https://user-images.githubusercontent.com/85597801/131273617-eb033973-a64f-4f63-9eba-1208d88e658c.png)
