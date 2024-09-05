Movie Ratings Analysis using Apache Spark (MapReduce)

Overview
In this project, I implemented a MapReduce-like framework using Apache Spark to analyze movie ratings data from a large dataset. The goal was to compute the average ratings for each movie and identify the top 10 movies with the highest average rating and the bottom 10 movies with the lowest average rating. This project leverages Spark's distributed computing capabilities to efficiently handle large-scale data and demonstrate how parallel data processing can be used to extract insights.

Objectives
Compute the average rating of each movie from a large dataset of user reviews.
Identify the top 10 highest-rated and bottom 10 lowest-rated movies.
Implement a MapReduce-like approach using Spark's RDD and DataFrame API.
Showcase the benefits of distributed computing for processing large datasets.

Project Structure
Data Loading: Load the ratings.csv dataset into a Spark DataFrame.
Mapping Phase: Convert the DataFrame into an RDD, generating key-value pairs (movie ID, rating and count).
Reducing Phase: Aggregate the ratings and counts by movie ID, then compute the average rating.
Result Analysis: Display the top 10 highest-rated and bottom 10 lowest-rated movies.

Results
The output will display:

The top 10 movies with the highest average ratings.
The bottom 10 movies with the lowest average ratings.

Conclusion
This project demonstrates the power of Apache Spark and MapReduce for processing and analyzing large-scale movie ratings data, allowing efficient extraction of key insights. Feel free to contribute and expand the project
