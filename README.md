# CS210

https://www.kaggle.com/datasets/pushpakhinglaspure/oscar-dataset)

https://www.kaggle.com/datasets/ashutoshdevpura/imdb-top-10000-movies-updated-august-2023

Description
This project aims to analyze the relationship between movies that have won Oscars and their IMDb ratings. By combining the Oscar dataset and the IMDb Top 10,000 movies dataset, we seek to understand whether winning an Oscar correlates with higher IMDb ratings and explore trends related to genres and release years.

Table of Contents
Motivation
Tools
Data Sources
Oscar Dataset
IMDb Top 10,000 Movies Dataset
Data Processing
Data Analysis
IMDb Ratings Comparison
Genre Distribution
Release Year Trends
Findings
Limitations
Future Work
Motivation
The Academy Awards (Oscars) are prestigious accolades in the film industry. This project seeks to determine if Oscar-winning movies have higher IMDb ratings compared to other movies and to analyze patterns in genres and release years among these films.

Tools
Python
Pandas: Data manipulation
NumPy: Numerical computations
Matplotlib and Seaborn: Data visualization
Jupyter Notebook
Data Sources
Oscar Dataset
Link: Oscar Dataset
Description: Contains information on Oscar winners, including movie titles, categories, and years.
IMDb Top 10,000 Movies Dataset
Link: IMDb Top 10,000 Movies
Description: Provides details on the top 10,000 movies from IMDb, including ratings, genres, directors, and release years.
Data Processing
Data Cleaning:

Handle missing values and duplicates.
Standardize movie titles and years for accurate merging.
Data Merging:

Merge datasets on movie titles and release years.
Create a new column indicating whether a movie is an Oscar winner.
Feature Selection:

Select relevant columns: title, year, genre, IMDb rating, Oscar winner flag.
Data Analysis
IMDb Ratings Comparison
Objective: Compare IMDb ratings between Oscar-winning movies and non-winning movies.

Method:

Calculate average IMDb ratings for both groups.
Perform t-tests to determine if differences are statistically significant.
Visualization:

Box plots and histograms of IMDb ratings for both groups.
Genre Distribution
Objective: Analyze the genre distribution among Oscar winners and compare it with non-winners.

Method:

Count the frequency of genres in both groups.
Identify the most common genres among Oscar winners.
Visualization:

Bar charts showing genre frequencies.
Release Year Trends
Objective: Examine trends in the number of Oscar-winning movies over the years.

Method:

Plot the number of Oscar-winning movies by decade.
Analyze any patterns or significant changes over time.
Visualization:

Line graphs showing the number of winners per decade.
Findings
IMDb Ratings:

Oscar-winning movies generally have higher average IMDb ratings than non-winners.
Genres:

Drama and Biography are more prevalent among Oscar winners compared to other genres.
Release Years:

An increasing trend in Oscar-winning movies in recent decades.
Limitations
Data Alignment:

Inconsistencies in movie titles and release years may affect merging accuracy.
Sample Bias:

The IMDb dataset includes only the top 10,000 movies, potentially biasing results toward higher-rated films.
Future Work
Expanded Dataset:

Include more movies beyond the top 10,000 for a comprehensive analysis.
Additional Factors:

Investigate other factors such as director influence, budget, and box office success.
Predictive Modeling:

Develop models to predict Oscar winners based on various features.
