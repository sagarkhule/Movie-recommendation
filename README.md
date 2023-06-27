# Movie-recommendation
Content Based Recommender System recommends movies similar to the movie user likes and analyses the sentiments on the reviews given by the user for that movie.

The details of the movies(title, genre, runtime, rating, poster, etc) are fetched using an API by TMDB, https://www.themoviedb.org/documentation/api, and using the IMDB id of the movie in the API, I did web scraping to get the reviews given by the user in the IMDB site using beautifulsoup4 and performed sentiment analysis on those reviews.
# How to get the API key?
Create an account in https://www.themoviedb.org/, click on the API link from the left hand sidebar in your account settings and fill all the details to apply for API key. If you are asked for the website URL, just give "NA" if you don't have one. You will see the API key in your API sidebar once your request is approved.
Sources of the datasets1

https://www.kaggle.com/datasets/carolzhangdc/imdb-5000-movie-dataset
https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset
https://en.wikipedia.org/wiki/List_of_American_films_of_2018
https://en.wikipedia.org/wiki/List_of_American_films_of_2019
https://en.wikipedia.org/wiki/List_of_American_films_of_2020
