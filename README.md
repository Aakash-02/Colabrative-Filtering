# Collaborative Filtering Movie Recommendation System

This project is a movie recommendation system based on collaborative filtering, a technique commonly used in recommendation systems. Collaborative filtering works by analyzing user ratings for items (e.g. movies) to find similarities between users and/or items, and then using these similarities to predict ratings for new items.

## Dataset

The dataset used for this project is the MovieLens 100K dataset, which consists of 100,000 ratings from 943 users on 1,682 movies. The dataset is split into a training set and a testing set, with 80% of the data used for training and 20% for testing.

## Model

The model used for this project is a neural network that uses user and item embeddings to predict the ratings of movies by users. The user and item embeddings are learned during training, and the predicted ratings are compared to the actual ratings to calculate the loss. The model is then optimized using backpropagation and gradient descent.

## Usage

To run the code, you can execute the `movie_recommendation.py` file in your terminal:

