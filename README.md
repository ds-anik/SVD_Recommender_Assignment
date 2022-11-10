# SVD_Recommender_Assignment

## Part 1:
In the first part the goal is to implement the dimensionality reduction technique Principal Component Analysis (PCA) to a very high dimensional data and use visualization to visualize in 2 dimensions. Note that we were not allowed to use the built-in PCA API provided by the sklearn library. Instead we implemented from the scratch.

- The tests are based on the variance ratio from reconstruction error computed by the `getVarianceRatio(Z, U, X, K)` function with a few K values. The ratios will be compared to the variance ratio obtained from the built-in PCA implementation in sklearn.
- The data on movie ratings train.csv is in data folder
- we applied PCA for the movies not for the users, and visualize the PCA in 2D with movie generes as labels


## Parts 2:

In the second part we  implemented a recommender system using SVD

- Used the data in data/train.csv and applied SVD
- Then used the k best components/concepts to predict the movie ratings for the user/movie pair in test.csv
- Write the predicted results in submission.csv


