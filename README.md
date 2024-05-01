# ML_Project50-MovieRecommendationEngine

### Movie Recommendation System with k-Nearest Neighbors
This project implements a movie recommendation engine using the k-Nearest Neighbors (kNN) algorithm on the MovieLens dataset. It recommends movies to users based on their past ratings and the ratings of similar users.

### Project Overview
This project addresses the problem of movie recommendation through the following steps:

#### Data Preprocessing:
Loads the MovieLens dataset containing movie information and user ratings.

Merges the datasets to create a user-movie rating matrix.

Analyzes user-movie interaction statistics.

#### k-Nearest Neighbor Algorithm:
Implements a kNN algorithm from scratch to find similar users based on their movie rating similarity.

Predicts movie ratings for a user based on the ratings of their k nearest neighbors.


#### Recommendation Generation:
Recommends movies to a user that they haven't watched yet, prioritizing those with the highest predicted ratings.

### Project Structure
#### The project is organized as follows:
data: Contains the MovieLens dataset files (movies.csv and ratings.csv).

utils: Includes helper functions for data preprocessing, similarity calculation, and recommendation generation.

main.py: The main script that loads data, implements the kNN algorithm, and generates movie recommendations.

### Getting Started
Clone the Repository:
```
https://github.com/Thireshsidda/ML_Project50-MovieRecommendationEngine.git
```

### Install Dependencies:
```
pip install pandas numpy scipy
```

### Run the Project

This will provide movie recommendations for a specific user based on their past ratings.

### Key Features
kNN algorithm implemented from scratch for user similarity calculation.

User-based collaborative filtering approach for movie recommendation.

Ability to retrieve favorite movies of a user and suggest personalized recommendations.

### Further Enhancements
Explore other recommendation algorithms like matrix factorization or deep learning techniques.

Implement user and movie profile analysis to refine recommendations based on user preferences and movie characteristics.

Integrate the recommendation system into a web application for user interaction.

This project provides a solid foundation for building a movie recommendation system using kNN. Feel free to experiment with different configurations and explore further improvements to enhance the recommendation accuracy and user experience.
