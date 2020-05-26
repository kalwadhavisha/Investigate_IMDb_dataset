# Investigate_IMDb_dataset

This report is a part of Udacity's Data Analyst Nanodegree Program. This report is s submission towards the Project: Investigate a dataset. The chosen dataset for this submission is The TMDb Movies Dataset. The reason to choose this topic is that almost everyone loves movies. Being a data analyst, the curiosity to know more about the factors influencing a movie budget or revenue is what makes this dataset very interesting to explore. 

## Objective

The questions to be answered in this report are:
- Which genres are most popular from year to year?
- What kinds of properties are associated with movies that have high revenues

## Tools

You can run the script using a Python integrated development environment (IDE). This script is written in Python 3, so you will need the Python 3.x version of the installer. The code was written in Jupyter Notebook.

## Dataset

File Name: tmdb-movies.csv
Variables:
Variables:

- id
- imdb_id
- popularity
- budget
- revenue
- original_title
- cast
- homepage
- director
- tagline
- keywords
- overview
- runtime
- genres
- production_companies
- release_date
- vote_count
- vote_average
- release_year
- budget_adj
- revenue_adj

## Conclusions

- To conclude the research on the topic 1: Which Genres are popular from year to year, the results obtained are not very specific or inclined to one result. It shows that the popular genre varies from year to year. It is not constant. But Drama and Comedy are one of the most popular ones among the given data.
- To conclude the research on the topic 2: What kinds of properties are associated with movies that have high revenues, the conclusions drawn for this research is that the numeric columns of "popularity, budget and vote_count" show the highest correlations.
- Every dataset or analysis has its own limitations. With the data provided, these were the conclusions that can be drawn. Main issue was with the missing data. Removing the missing data causes a lot of data loss but the missing data in this data were difficult to replace too. Hence, had to be removed. The data did not have any issues with being a tidy dataset but there were a lot of quality issues. Missing values and too many parameters in a single feature separated by delimiters. If the data had been of better quality then the analysis results could have been more specific and accurate.
