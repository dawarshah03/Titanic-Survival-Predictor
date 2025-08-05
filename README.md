# Titanic Survival Predictor

## Problem
We are given a Titanic dataset with details about each passenger. Our goal is to predict whether a passenger survived or not based on their personal and travel information.

## Solution
We used Gaussian Naive Bayes (GaussianNB) for binary classification. Categorical columns were encoded using Label Encoding, and numerical features were scaled using MinMaxScaler. The model was trained and evaluated using a train-test split.

## What Are We Finding
We are predicting the Survival of Titanic passengers using a supervised machine learning model.

## Columns Used
Pclass

Sex

Age

Fare

We dropped columns like PassengerId, Name, Ticket, SibSp, Parch and Cabin to reduce noise and prevent data leakage.

## Accuracy
It was 0.7985074626865671
