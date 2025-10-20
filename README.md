🌸 Iris Flower Classification
📘 Project Overview
This project demonstrates a machine learning classification task using the famous Iris dataset.
The goal is to predict the species of iris flowers (Setosa, Versicolor, or Virginica) based on features such as:
Sepal length
Sepal width
Petal length
Petal width
This project is part of my AI Engineering learning journey, focusing on applying scikit-learn for real-world predictive modeling.
🧠 Objectives
Understand supervised learning concepts
Perform data preprocessing and visualization
Train a classification model using algorithms like Logistic Regression, Decision Tree, and Random Forest
Evaluate model accuracy and interpret the results
📊 Dataset
The Iris dataset is available directly in scikit-learn:
from sklearn.datasets import load_iris
iris = load_iris()
It contains 150 samples, 4 features, and 3 target classes.
🧩 Technologies Used
Python 3.x
pandas
numpy
matplotlib / seaborn
scikit-learn
Jupyter Notebook
🚀 Steps Performed
Load and explore the dataset
Visualize feature relationships
Split data into training and testing sets
Train and compare different models
Evaluate results using accuracy and confusion matrix
📈 Model Performance
Logistic Regression achieved an accuracy of around 97–99%
Random Forest also performed strongly
Confusion matrix shows near-perfect classification
🧰 How to Run
Clone this repository:
git clone https://github.com/arsalaniltaf001/iris-classification.git
cd iris-classification
Run the notebook:
jupyter notebook iris_classification.ipynb
🧑‍💻 Author
Muhammad Arsalan
AI Engineer (in training) | MS Computer Science – CUST
⭐ Future Work
Try additional models (SVM, KNN)
Deploy the model using Streamlit or Flask
Visualize predictions interactively