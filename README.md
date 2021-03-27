# movie_recommendation_system
Model to classify if a movie will be a success or not. Through this model, we also aim at discovering what features have the most significant impact in determining the success of a movie.
This project is divided into two parts:

1. Analysis and prediction model:

	Exploratory Data Analysis, which is performed on Movie Metadata about Movie Revenues, Genre, Budgets, etc. through the years.
	Model to classify if a movie will be a success or not. Through this model, we also aim at discovering what features have the most significant impact in determining the success of a movie.
  A Classifier that identifies if a movie will be a hit or will make the producers lose money.
  
2. Movie Recommender Systems:
This part is focused around building Content based recommendation engines using the scikit-learn library. This type of recommendation systems takes in a movie that a user currently likes as input. Then it analyzes the contents (storyline, genre, cast, director etc.) of the movie to find out other movies which have similar content. Then it ranks similar movies according to their similarity scores and recommends the most relevant movies to the user.

The Data:
Dataset link : https://www.kaggle.com/rounakbanik/the-movies-dataset/data
movies_metadata.csv: The main Movies Metadata file. Contains information on around 45,000 movies featured in the Full MovieLens dataset. Features include posters, backdrops, budget, revenue, release dates, languages, production countries and companies. The movies available in this dataset are in correspondence with the movies that are listed in the MovieLens Latest Full Dataset comprising of 26 million ratings on 45,466 movies from 27,000 users, comprises of 24 features.
