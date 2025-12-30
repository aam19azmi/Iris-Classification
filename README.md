🌸 Iris Flower Classification

📌 Google Colab Notebook:
https://colab.research.google.com/drive/1-BhMob0z2oRQrKGbORH5AF9ivD7HUYeW?usp=sharing

Overview

This project demonstrates a basic yet complete machine learning classification pipeline using the classic Iris Flower Dataset.
The objective is to classify Iris flower species using multiple supervised learning algorithms and compare their performance.

The entire project is implemented and executed using Google Colab, making it easy to reproduce and explore.

Project Objectives

Perform exploratory data analysis (EDA)

Train and compare multiple classification models:

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

Logistic Regression

Evaluate model performance using:

Accuracy score

Confusion matrix

Analyze and interpret the results

Dataset

Name: Iris Flower Dataset

Number of Samples: 150

Features:

Sepal Length

Sepal Width

Petal Length

Petal Width

Target Classes:

Iris-setosa

Iris-versicolor

Iris-virginica

The dataset file Iris.csv is included directly in this repository.

Original source (Kaggle):
https://www.kaggle.com/datasets/uciml/iris

Models Used

K-Nearest Neighbors (KNN)

Support Vector Machine (SVM)

Logistic Regression

All models are trained using the same train-test split to ensure a fair and consistent comparison.

Results Summary

All three models achieved 100% accuracy on the test dataset.

This strong performance is expected due to:

Good class separability among Iris species

Highly informative numerical features

Small, clean dataset with no missing values

The results highlight how classical machine learning models can perform exceptionally well on well-structured datasets.

Repository Contents

Iris.csv — Dataset file

iris_classification.ipynb — Main Google Colab notebook

iris_classification - Colab.pdf — Exported notebook results (PDF)

README.md — Project documentation

How to Run

This project is designed to be run in Google Colab.

Option 1: Run Using Kaggle API

Open iris_classification.ipynb in Google Colab.

Locate the Kaggle API configuration cell.

Fill in your own Kaggle credentials:

import os

os.environ["KAGGLE_USERNAME"] = "your_kaggle_username"
os.environ["KAGGLE_API_KEY"] = "your_kaggle_api_token"


Run all notebook cells sequentially.

📌 Note: A valid Kaggle account and API token are required for this option.

Option 2: Run Using the Included Dataset (Without Kaggle API)

Open iris_classification.ipynb in Google Colab.

Upload the provided Iris.csv file when prompted, or ensure it is located in the working directory.

Run all cells to reproduce the results.

📌 This option does not require Kaggle credentials.

Conclusion

This project provides a clear and concise demonstration of classical machine learning classification techniques.
Despite its simplicity, it successfully showcases essential ML concepts such as data exploration, model training, evaluation, and result interpretation.

Author

Azmi Jalaluddin Amron
Machine Learning / Data Science Portfolio Project

License

This project is intended for educational and portfolio purposes.