# Movie rating prediction
## Overview
This project uses a Recurrent Neural Network (RNN) with GRU layers to predict movie ratings based on user and item embeddings. The dataset used is the MovieLens 100k dataset, which consists of 100,000 ratings from 943 users on 1682 movies.
### Dataset
The dataset used in this project is the MovieLens 100k dataset, which can be downloaded from [here](https://files.grouplens.org/datasets/movielens/ml-100k/u.data).
### Data Visualization
Basic data analysis is performed using histograms to visualize the distribution of ratings, the number of ratings per user, and the number of ratings per movie.
### Model Building
A Recurrent Neural Network (RNN) with GRU layers is created. The model uses embeddings for users and movies, which are concatenated and passed through a GRU layer, followed by a linear layer to make predictions.
### Model Training
The model is trained on 80% of the data using the Adam optimizer and MSELoss function. Each epoch calculates losses on both the training and validation sets. Early stopping is used to prevent overfitting.
### Model Evaluation
After training, the model is evaluated on the validation set by calculating the mean absolute error (MAE) and visualizing the actual versus predicted ratings.
### Conclusions
The model demonstrates the ability to predict movie ratings, but its performance can be improved by tuning hyperparameters, using more advanced architectures, or incorporating additional features.
## Requirements
Libs requirements:
1. Python 3.x
2. pandas
3. numpy
4. matplotlib
5. seaborn
6. scikit-learn
7. torch
8. tqdm






