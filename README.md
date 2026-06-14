# dipeshvbante31-Random-Forest-Classification-is-a-supervised-machine-learning-exp
# Iris Flower Classification using Machine Learning 

A simple and interactive Machine Learning web application built with Streamlit that predicts the species of an Iris flower based on its physical measurements.

## Overview

This project uses the famous Iris dataset and a Random Forest Classifier to classify flowers into one of three species:

* Iris Setosa
* Iris Versicolor
* Iris Virginica

Users can adjust flower measurements using interactive sliders and instantly receive predictions from the trained machine learning model.

## Features

✅ Interactive Streamlit Dashboard

✅ Real-time Iris Species Prediction

✅ Random Forest Machine Learning Model

✅ User-friendly Sidebar Controls

✅ Fast and Lightweight Application

✅ Uses the Built-in Scikit-learn Iris Dataset

## Tech Stack

* Python
* Streamlit
* Pandas
* Scikit-learn

## How It Works

1. Load the Iris dataset from Scikit-learn.
2. Train a Random Forest Classifier on the dataset.
3. Take user inputs for:

   * Sepal Length
   * Sepal Width
   * Petal Length
   * Petal Width
4. Generate a prediction based on the entered values.
5. Display the predicted Iris species instantly.

## Installation

```bash
git clone https://github.com/yourusername/iris-flower-classifier.git

cd iris-flower-classifier

pip install -r requirements.txt

streamlit run app.py
```

## Project Structure

```text
iris-flower-classifier/
│
├── app.py
├── requirements.txt
└── README.md
```

## Machine Learning Model

The application uses a Random Forest Classifier from Scikit-learn, which is trained on the complete Iris dataset and provides highly accurate predictions.

## Future Improvements

* Prediction probabilities
* Feature importance visualization
* Interactive charts and graphs
* Model comparison (Random Forest, SVM, KNN)
* Deployment on Streamlit Cloud

## Author

Dipesh Vishnu Bante

⭐ If you found this project useful, consider giving it a star on GitHub!

