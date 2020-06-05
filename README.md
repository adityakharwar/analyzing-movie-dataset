### Project Overview

 Analyzing movie data set


### Learnings from the project

 Data wrangling, Functions, Strings


### Approach taken to solve the problem

 Different function that you would require to define fir this project has been mentioned in the code block . All the parameters and task a function would do, has been mentioned there.
 Subset the movies dataset such that the header is removed from the list and store it back in movies
Delete the wrong data. Explore row #4553. You will see that as apart from the id, description, status and title, no other information is available.
Hence drop this row.
Using explore_data() with appropriate parameters, view the details of the first 5 movies.
Our dataset might have more than one entry for a movie. Call duplicate_and_unique_movies() with index of the name to check the same.
We saw that there are 3 movies for which there are multiple entries.
Create a dictionary, reviews_max that will have the name of the movie as key, and the maximum number of reviews as values.
Create a list movies_clean, which will filter out duplicate movies and contain the rows with the maximum number of reviews for duplicate movies, as stored in 'review_max'.
Calling movies_lang(), extract all the English movies and store it in movies_en.
Call the rate_bucket function to see the movies with a rating higher than 8 and store the resulting list in high_rated_movies.


### Challenges faced

 Strings and function overcome ---- online lecture


### Additional pointers

 None


