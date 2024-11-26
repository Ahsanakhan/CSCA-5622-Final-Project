# Predicting Hazardous Nearest Earth Objects (1910-2024)
#### Ahsan Khan | 11-26-2024
##### [Github Repository](https://github.com/Ahsanakhan/CSCA-5622-Final-Project)
## Introduction

Asteroids and other celestial objects that come close to Earth's orbit are classified as Nearest Earth Objects (NEOs). While many of these objects pose no threat, some have the potential to cause significant harm if they were to collide with our planet. NASA monitors these NEOs and classifies them based on their potential hazard level. In this project, we will analyze data on [NASA | Nearest Earth Objects (1910-2024)](https://www.kaggle.com/datasets/ivansher/nasa-nearest-earth-objects-1910-2024/data) kaggle dataset to predict whether a given NEO is hazardous.

## Dataset Overview

This dataset contains over 338,000 records of NEOs, each described by various parameters such as size, velocity, and distance from Earth. Our goal is to use machine learning techniques to build a predictive model that can accurately classify whether an NEO is hazardous or not based on these parameters.

## Project Objective

The objective of this project is to develop a machine learning model that can predict the `is_hazardous` classification of NEOs. We will start by performing exploratory data analysis (EDA) to understand the distribution and relationships in the data. We will then preprocess the data, engineer relevant features, and experiment with various machine learning models, including Logistic Regression, Random Forest, Gradient Boosting, Support Vector Machines (SVM), and Ensemble methods. Finally, we will evaluate the models' performance and select the best model for predicting hazardous NEOs.

## Methodology

1. **Data Cleaning and EDA:** We will begin by loading the dataset and performing exploratory data analysis (EDA) to understand the data distribution, identify missing values, and explore relationships between variables.
2. **Feature Engineering:** Based on our EDA, we will create new features or modify existing ones to improve model performance.
3. **Model Building:** We will train and evaluate several machine learning models, including Logistic Regression, Random Forest, Gradient Boosting, SVM, and Ensemble models, to determine which one performs best on this dataset.
4. **Model Evaluation:** We will use metrics such as accuracy, precision, recall, and F1-score to evaluate the performance of our models and select the best one.
5. **Hyperparameter Tuning:** To explore a range of hyperparameters to optimize best performing model.
6. **Results and Analysis:** Finally, we will summarize our findings.
7. **Conclusion and Discussion:** We will discuss the implications of our results, and suggest possible improvements or future work.
