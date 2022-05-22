# Movies-ETL
## Overview
Amazing Prime loves the dataset and wants to keep it updated on a daily basis. Britta needs your help to create an automated pipeline that takes in new data, performs the appropriate transformations, and loads the data into existing tables. You’ll need to refactor the code from this module to create one function that takes in the three files—Wikipedia data, Kaggle metadata, and the MovieLens rating data—and performs the ETL process by adding the data to a PostgreSQL database.

## Deliverable
- Deliverable 1: Write an ETL Function to Read Three Data Files
- Deliverable 2: Extract and Transform the Wikipedia Data
- Deliverable 3: Extract and Transform the Kaggle data
- Deliverable 4: Create the Movie Database


## Results
The results database we created consists of two tables (see images below)

1. Movie table with 6,051 rows of data that represent the movie titles.  This table also consists of 31 columns with production related information.

![retiring_titles.png](https://github.com/diercz/Movies-ETL/blob/main/Images/movies_query.png)

2. Ratings table with 26,024,289 rows of data, each representing a rating 1-5 with five columsn of data.

![retiring_titles.png](https://github.com/diercz/Movies-ETL/blob/main/Images/ratings_query.png)