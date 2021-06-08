# ETL Project

### Team Members  
Hema Vyas, Matthew Canady, Lindsay Reynolds

### Project Overview/Objective
The project will extract data from CSV files to Pandas. Data will be transformed and loaded to a relational database.
* Movies are filtered for years > 2000
* Ratings are filtered for weighted_average_vote >= 8 
* The project is summarized in the Project Report

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

Note: IMDb_title_id will be the primary key if tables are joined

### Requirements
* Remove null values and remove duplicated rows
* Filter for the columns needed for each table
* Filter for movies after the year 2000
* Filter for the weighted_average_vote >=8

### Data Sources  
Kaggle: IMDB movies extensive dataset  
[Movies](https://www.kaggle.com/stefanoleone992/imdb-extensive-dataset?select=IMDb+movies.csv)  
[Ratings](https://www.kaggle.com/stefanoleone992/imdb-extensive-dataset?select=IMDb+ratings.csv)

