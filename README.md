# Titanic Survival Prediction

## Project Overview
This project uses machine learning algorithms to predict the survival of passengers on the Titanic based on key features like age, gender, class, and fare. The goal is to apply different classification models and compare their performance to achieve the most accurate predictions.

## Dataset
The dataset used in this project is the famous [Titanic dataset](https://www.kaggle.com/c/titanic) available from Kaggle. It contains data on passengers, such as their age, ticket class, sex, fare paid, and whether they survived the Titanic disaster.

## Algorithms Used
We have used the following machine learning algorithms to predict passenger survival:

- Logistic Regression
- Support Vector Classifier (SVC)
- Decision Tree Classifier
- Random Forest Classifier
- K-Nearest Neighbors (KNN) Classifier

## Model Evaluation
Each model's performance is evaluated using accuracy, precision, recall, F1-score, and confusion matrix. The Random Forest Classifier, with 1000 estimators, was found to perform the best among the models tested.

## Requirements
To run this project, you need to install the following dependencies:

- Python 3.x
- NumPy
- pandas
- scikit-learn
- matplotlib (optional for visualizing results)

You can install the required dependencies using pip:

```bash
pip install numpy pandas scikit-learn matplotlib
