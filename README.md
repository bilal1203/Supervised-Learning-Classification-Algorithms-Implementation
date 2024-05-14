# Supervised Learning Classification Algorithms Implementation

Welcome to the Supervised Learning Classification Algorithms Implementation project! This project aims to provide implementations and explanations of various supervised learning classification algorithms using the Space Titanic Dataset.

## Overview
In this project, we explore different supervised learning classification algorithms to predict whether a passenger was transported to an alternate dimension during the Spaceship Titanic's collision with a spacetime anomaly. We provide implementations of the following algorithms:

### Ensemble Methods:
- GradientBoostingClassifier
- AdaBoostClassifier
- RandomForestClassifier
- BaggingClassifier
- XGBClassifier
- LGBMClassifier
- CatBoostClassifier
- ExtraTreesClassifier

### Linear Models:
- RidgeClassifierCV
- LogisticRegressionCV
- PassiveAggressiveClassifier
- Perceptron
- SGDClassifier

### Support Vector Machines (SVM):
- SVC
- NuSVC
- LinearSVC

### Naive Bayes:
- BernoulliNB
- GaussianNB

### Discriminant Analysis:
- LinearDiscriminantAnalysis
- QuadraticDiscriminantAnalysis

### Decision Trees:
- DecisionTreeClassifier
- ExtraTreeClassifier

### Nearest Neighbors:
- KNeighborsClassifier

### Gaussian Processes:
- GaussianProcessClassifier

## Project Structure
The project is organized as follows:

- **Data Preprocessing:** Contains notebooks for data cleaning, transformation, feature engineering, and feature selection.
- **Exploratory Data Analysis (EDA):** Includes notebooks for exploring and analyzing the dataset.
- **Model Implementation:** Each classifier has its folder containing a Jupyter notebook for implementation and a `Notes.md` file explaining how the method works and other relevant details.
- **Model Comparison:** This folder contains a notebook (`Model_Comparison.ipynb`) where each classifier is implemented with the best model parameters found through cross-validation and hyperparameter tuning, and their results are compared.
- **README.md:** You are here! This file provides an overview of the project and instructions for usage.

## Getting Started
To get started with the project, follow these steps:

1. Clone this repository to your local machine.
2. Install the necessary dependencies listed in `requirements.txt`.
3. Explore the `Data Preprocessing` and `EDA` notebooks to understand the dataset.
4. Implement and explore different classifiers in the `Model Implementation` notebooks.
5. Compare the performance of classifiers with optimized parameters in the `Model Comparison` notebook.
6. Feel free to customize and extend the project according to your needs!

## Dataset Description
The Space Titanic Dataset contains personal records of passengers onboard the Spaceship Titanic during its ill-fated voyage through the cosmos. This dataset serves as the backbone for our classification task, aiming to predict whether a passenger was transported to an alternate dimension following the collision with a spacetime anomaly.

### Features
The dataset comprises various features that provide insights into the passengers' profiles and activities onboard the spaceship, including:

- **PassengerId:** A unique identifier assigned to each passenger.
- **HomePlanet:** The planet of origin for each passenger.
- **CryoSleep:** Indicator of whether the passenger opted for suspended animation.
- **Cabin:** Cabin number where the passenger stayed.
- **Destination:** Intended destination planet.
- **Age:** Age of the passenger.
- **VIP:** Indicator of VIP service availed.
- **RoomService, FoodCourt, ShoppingMall, Spa, VRDeck:** Expenses incurred at onboard amenities.
- **Name:** Passenger's name.

### Target Variable
- **Transported:** Binary indicator (True/False) of whether a passenger was transported to an alternate dimension.

### Dataset Size
- **Training Set:** Approximately 8,700 records (two-thirds of passengers).
- **Test Set:** Approximately 4,300 records (one-third of passengers).

## License
This project is licensed under the [MIT License](LICENSE).
