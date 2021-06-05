# ETL Project

### Team Members  
Hema Vyas, Matthew Canady, Lindsay Reynolds

### Project Overview/Objective
The project will extract data from CSV files to Pandas. Data will be transformed and loaded to a relational database.
* Movies will be grouped by decade and movies with weighted_average_vote >= 8 will be displayed 
* The decade with the highest rated movies will be identified
* The top five languages will be identified
* The project will be summarized in the Project Report

### Data Destination
A relational database will be created in postgres with a movies table and a ratings table

Structure of movies table (text unless otherwise identified):  
* imdb_title_id 
* title
* year (INT) 
* language
* country  

Structure of ratings table (text unless otherwise identified)
* imdb_title_id
* total_votes
* weighted_average_vote (FLOAT)
* mean_vote (FLOAT)

Note: IMDb_title_id is going to be the primary key

### Requirements
* Remove null values and remove duplicated rows
* Filter for the columns needed for each table
* Group movies by decade
* Filter for the weighted_average_vote >=8
* Group movies by language and identify the top 5

### Data Sources  
Kaggle: IMDB movies extensive dataset  
[Movies](https://www.kaggle.com/stefanoleone992/imdb-extensive-dataset?select=IMDb+movies.csv)  
[Ratings](https://www.kaggle.com/stefanoleone992/imdb-extensive-dataset?select=IMDb+ratings.csv)

