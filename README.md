# Arabica Coffee Quality Prediction
## Introduction
Coffee is one of the most consumed beverages worldwide, and its quality significantly impacts consumer preferences and market prices. This project aims to predict coffee quality based on various physical and chemical characteristics.

## Objectives
Develop a model that can predict an Arabica's quality
Analyze the influence of different factors (e.g., acidity, sweetness, bitterness) on an Arabica's aftertaste.

## Data Collection
The dataset consists of samples from various coffee origins, including features such as species of coffee, sweetness, aroma, acidity, flavor, etc. It is sourced from Kaggle. We filtered the coffee species to only Arabica.
https://drive.google.com/drive/folders/1q2bklehgS3nUs4VZk0T5MCdeIpCUjUrd?usp=sharing

## Methodology
Data Preprocessing: Replacing and dropping missing values and outlier values
Data Visualization : Visualizing distributions, comparison of Arabica qualities in between countries.
Feature Selection: Selected relevant features impacting an Arabica's aftertaste.
Model Selection: Compared 2 models, Random Forest and Multi Linear Regression.
Model Training and Evaluation: 
- Random Forest : Achieved an error (RMSE) of 0.168
- Multi Linear Regression : Achieved an error (RMSE) of 0.096

## Conclusion
Our Multi Linear Regression Model is more capable in predicting an Arabica's aftertaste based on other factors, with an error that is quite small.
