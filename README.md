# California Housing Price Prediction
This repository contains a Jupyter Notebook (house_price_prediction.ipynb) that demonstrates a complete machine learning workflow to predict house prices using the California Housing dataset.

Project Overview
The goal of this project is to build and evaluate a regression model that can predict median house values based on various features of housing districts in California.

Dataset
The project utilizes the California Housing dataset, which includes features such as median income, house age, average number of rooms, average number of bedrooms, population, average occupancy, latitude, and longitude. The target variable is the median house value for each district.

Workflow
The notebook follows these steps:

Data Loading: Loads the California Housing dataset.
Data Exploration: Includes initial data inspection and visualization, such as a correlation heatmap, to understand the relationships between features and the target variable.
Data Preparation: Splits the dataset into training and testing sets to train and evaluate the model.
Model Training: Trains an XGBoost Regressor model on the training data.
Model Evaluation: Evaluates the trained model's performance using metrics like R-squared and Mean Absolute Error on both the training and testing sets.
Visualization: Creates scatter plots to visualize the relationship between the actual and predicted house prices.
