# Movie-recommender
Phase 4 project
## Group Members
1. Elsie Juma
2. Iain Mosima
3. Ibrahim Hafiz
4. Elsie Kiprop
5. Davis Obatsa
6. Peter Kigoth
7. Oscar Karuga
## Business Understanding
Cinemy,a movie streaming company asked their users to rate them on google play store. The feedback received was that the movies recommended to the users didn't match their interests thus most customers were dissatisfied. They have approached us, a data analytics company to help them solve their problem. We will therefore, build a movie recommender system that will aid in suggesting top 5 movies to the streaming site users based on their ratings  and the genres they prefer.
## Metrics for success
We will use RSME and MAE as our metric for success,the model having the lowest scores being our best model.
## Data Understanding
The data used has been sourced from MovieLens dataset from the GroupLens research lab at the University of Minnesota.
It contains 100836 ratings and 3683 tag applications across 9742 movies. These data were created by 610 users.
The dataset is distributed among four csv files:
1.```links.csv```
2.```movies.csv```
3.```ratings.csv```
4.```tags.csv```

1.```Movies.csv```
Each line of this file after the header row represents one movie, and has the following columns:
movieId: Unique id for each movie
title: Name of movies followed by their year of release
genres: categories that a movie might fall into separated by |
2.```Links.csv```
The file `links.csv` contains indentifiers that can be used to link this data to other data sources like IMDb. Each line of this file after the header row represents one imdb link, and has the following columns:

- movieId: Unique id for each movie as used by https://movielens.org.
- imdbId: Unique id for each movie as used by http://www.imdb.com.
- tmdbId: Unique id for each movie as used by https://www.themoviedb.org.

3.```Tags.csv.```
 Each line of this file after the header row represents one tag applied to one movie by one user, and has the following columns:
- userId: Unique id for each user
- movieId: Unique id for each movie
- tag: User-generated metadata about the movie in forms of short meaningful phrases
- timestamp: Time when tag was provided by user
4.```Ratings.csv```
Each line of this file after the header row represents one rating, and has the following columns:
- userId: Unique id for each user
- movieId: Unique id for each movie
- rating: Rating given by userId for movieId. Ratings are made on a 5-star scale with 0.5 increments.
- timestamp: Time when rating was given

