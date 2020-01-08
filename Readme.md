In this repository I stored the code used in my Movie Mate Recommendation Engine project, in which I compute similarities in MovieLens users' movie taste and find the users with a movie taste that best resembles my own using Python. For this project I used the MovieLens 20M dataset retrieved from: https://grouplens.org/datasets/movielens

A more detailed look at this project can be found on my online portfolio (https://christheunissen.github.io/ChrisTheunissen/Movie%20Mate%20Recommendation%20Engine.html)

The csv file contains my own movie ratings in the same format as the ratings from the MovieLens dataset.

My first approach involves computing a user-item matrix and consequently computing the distance between the users' set of movie ratings for movies that both users watched. The code for this can be found in the "movielens recommendations.ipynb" notebook.

My second approach makes use of singular value decomposition to reduce the dimensionality of the user-item matrix and extract user taste profiles which I then compute the distance between to find the most similar users.
This approach can be found in the "SVD.ipynb" notebook. However, the tables produced by the movielens recommendations notebook are required for the SVD notebook to work.





