# House Price Prediction using Linear Regression

A beginner machine learning project for predicting median house values using Linear Regression and the California Housing dataset.

## Overview

This project demonstrates the basic end-to-end workflow of a regression machine learning problem using Python and Scikit-learn.

The project covers:

- Loading a dataset
- Exploring the dataset
- Checking for missing values
- Separating features and target
- Splitting data into training and testing sets
- Training a Linear Regression model
- Making predictions
- Evaluating model performance
- Visualizing predictions and errors
- Examining model coefficients
- Saving the trained model

The model was trained using Google Colab.

## Objective

The objective of this project is to predict median house values based on different characteristics of the surrounding area, such as median income, house age, average rooms, population, and geographic location.

The main goal of this project was to gain hands-on experience with the complete machine learning workflow.

## Dataset

The project uses the California Housing dataset provided by Scikit-learn.

### Dataset Information

- Total observations: 20,640
- Input features: 8
- Target variable: 1

### Features

| Feature | Description |
|---|---|
| `MedInc` | Median income |
| `HouseAge` | Median house age |
| `AveRooms` | Average number of rooms |
| `AveBedrms` | Average number of bedrooms |
| `Population` | Population of the area |
| `AveOccup` | Average occupancy |
| `Latitude` | Latitude |
| `Longitude` | Longitude |

### Target

`MedHouseVal` — Median house value.

## Machine Learning Workflow

```text
Dataset
   ↓
Data Exploration
   ↓
Missing Value Check
   ↓
Feature / Target Separation
   ↓
Train-Test Split
   ↓
Linear Regression
   ↓
Model Training
   ↓
Prediction
   ↓
Model Evaluation
   ↓
Visualization
   ↓
Model Saving
```