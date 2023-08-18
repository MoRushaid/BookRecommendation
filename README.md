# BookRecommendation
A book recommendation algorithm is created using K-Nearest Neighbors.

The Book-Crossings dataset is used for this and it contains 1.1 million ratings (scale of 1-10) of 270,000 books by 90,000 users.

After importing and cleaning the data, NearestNeighbors from sklearn.neighbors is used to develop a model that shows books that are similar to a given book. The Nearest Neighbors algorithm measures the distance to determine the “closeness” of instances.

A function named get_recommends takes a book title (from the dataset) as an argument and returns a list of 5 similar books with their distances from the book argument.
