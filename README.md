**READ ME**

**Overview**
This repository contains code for collaborative filtering using item-kNN and SVD algorithms. These algorithms are applied to the MovieLens dataset, which was collected by the GroupLens Research Project at the University of Minnesota. The dataset consists of 1,000,209 anonymous ratings of approximately 3,900 movies made by 6,040 MovieLens users who joined MovieLens in 2000.

**Source**
F. Maxwell Harper and Joseph A. Konstan. 2015. The MovieLens Datasets: History and Context. ACM Transactions on Interactive Intelligent Systems (TiiS) 5, 4, Article 19 (December 2015), 19 pages. DOI: http://dx.doi.org/10.1145/2827872  

**Dataset Description**
The MovieLens dataset consists of user ratings for movies. Specifically, it includes the following details:
- 1,000,209 ratings
- Approximately 3,900 movies
- 6,040 users who joined MovieLens in 2000

**Algorithms**
This repository implements collaborative filtering using two algorithms:

- Item-kNN (Item-based k-Nearest Neighbors): This algorithm computes the similarity between items (movies) based on user ratings and predicts ratings for a user by considering ratings of similar items.
- SVD (Singular Value Decomposition): SVD is a matrix factorization technique used for recommendation systems. It decomposes the user-item rating matrix into lower-dimensional matrices and predicts missing ratings using the derived matrices.

**Note**
This code is provided for educational purposes and experimentation with collaborative filtering algorithms. It may require modifications for use in production environments or with different datasets.
Also, please refer to the original paper by Harper and Konstan for more details about the MovieLens dataset and its usage.
