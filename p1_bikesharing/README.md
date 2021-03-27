# Udacity Deep Learning Nanodegree - Project 1: Bikesharing
Bike-sharing regression model.  Project 1 for Udacity's Deep Learning Nanodegree

Original repository: https://github.com/udacity/deep-learning-v2-pytorch/tree/master/project-bikesharing


### Introduction
In this project, you will build your first neural network and use it to predict daily bike rental ridership. We've provided some of the code, but left the implementation of the neural network up to you (for the most part). After you've submitted this project, feel free to explore the data and the model more


### Results

#### Loss Chart
![Chart of Training and Validation Loss](/assets/bikesharing_loss.png)

#### Comparison
![Comparison of Predicted Usage vs Actual](/assets/bikesharing_prediction-vs-actual.png)

The model predicts well on "normal" weeks and weekends, showing dips in usage for Saturday and Sunday. However, it does not work well during the holidays due it being outlying data.
