
# Collect datasets
moviedata.ipynb, oscar.ipynb

From IMDB, we obtained for each movie: movie title, IMDB rating, plot description, budget, box office gross, opening weekend gross, runtime, genres and release date. Also from IMDB, we obtained the number of Academy Awards that actors and directors in each movie had won prior to that movie, and also the number of Best Picture films that actors and directors in each movie had been involved in, also prior to that movie. In order to stay true to our goal of only considering factors known before a movie’s release, we considered only awards that had been received prior.

From Rotten Tomatoes, we obtained critic score, audience score, MPAA rating, actors and director. 

# Clean datasets:
cleandata.ipynb

Many features are missing from many movies and it must be handled. All these features are necessary for analysis, so the movie is dropped if any of these features are missing. We have three monetary attributes: budget, global gross profit, and opening weekend returns. In order to increase the utility of these fields, we accounted for inflation. For instance: budget = budget * (USD in 2023 / 1 USD in each year of the movie). 

After data collection and cleaning, we have the dataset which contains 16 variables for 5584 movies.

# Prediction
classification.ipynb

we use Logistics Regression, KNN, Decision Tree, Random Forest to predict for box office gross, imdb_rating, audience score, critic score of the movie.

# Reference
Jeffrey Ericson & Jesse Grodman, A predictor for movie success, CS229, Stanford University

Introduction to Business Analytics course notes

https://github.com/timothyng-164/Movie-Success-Predictor 

www.imdb.com

www.rottentomatoes.com

https://www.calculator.net/inflation-calculator.html? 

