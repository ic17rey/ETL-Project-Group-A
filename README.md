# ETL Project

### Team Members  
Hema Vyas, Matthew Canady, Lindsay Reynolds

### Project Overview/Objective
Group movies by decade and display movies that are weighted_average_vote >= 8  
Identify what decade has the highest rated movies
Identify the top five languages

From data sources, these fields will be used:  
Movies: imdb_title_id, title, year, language  
Ratings: imdb_title_id, total_votes, weighted_average_vote, mean_vote

Note: IMDb_title_id is going to be the primary key.

The project will be summarized in the Project Report.

### Data Destination
A relational database in pgAdmin 4.

### Requirements
Remove null values and remove duplicated rows.

### Data Sources  
Kaggle: IMDB movies extensive dataset  
[Movies](https://www.kaggle.com/stefanoleone992/imdb-extensive-dataset?select=IMDb+movies.csv)  
[Ratings](https://www.kaggle.com/stefanoleone992/imdb-extensive-dataset?select=IMDb+ratings.csv)

