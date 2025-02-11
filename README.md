# Rock vs Mine Prediction Using Sonar Data
## Overview

Outwardly SONAR technique has exploited the discovery of rocks and minerals which would have been very difficult otherwise. The technique exploits certain parameters which will aid to detect the surface targets or obstacle such as a rock or a mine. Machine learning has drawn the attention of maximum part of today’s emerging technology, related from banking to many consumer and product based industries, by showing the advancements in the predictive analytics.
This project applies Logistic Regression to classify sonar signals as either rock or mine based on frequency response data. The goal is to develop a binary classification model that can accurately distinguish between the two categories.

## Dataset

The dataset has been collected from UCI Repository. It has come across 61 features which define and differentiate Rocks and Mines and comprises of 209 samples. This data is used for training and testing purpose. The Last column in this dataset indicates that, whether it's a mine or a rock, which is useful in prediction. The dataset is included in this repository.

R (Rock) – Sonar signal reflected from a rock.

M (Mine) – Sonar signal reflected from a metal object (mine).

## Objective

Build a Logistic Regression model for binary classification.
Preprocess the data, trained and tested the model and Evaluated the model

## Model
The model used here is  **Logistic Regression**. Logistic regression is a statistical model that in its basic form uses a logistic function to model a binary dependent variable. Logistic Regression uses a sigmoid or logit function which will squash the best fit straight line that will map any values including the exceeding values from 0 to 1 range. So it forms an “S” shaped curve. Sigmoid func. removes the effect of outlier and makes the output between 0 to 1.
As it a binary classification model it is perfect to predict if an object is mine or rock based on the sonar data.



## Technologies & Libraries 
Python

Pandas & NumPy (Data Manipulation)

Scikit-Learn (Machine Learning & Model Evaluation)

## Implementation Steps
Data Preprocessing

Load and explore the dataset.

Scale the features for better model performance.

Model Training

Train a Logistic Regression classifier on the dataset.

Model Evaluation

Evaluated the model using accuracy_score.
 
