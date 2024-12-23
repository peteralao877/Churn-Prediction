# Churn-Prediction

This repository contains a project focused on predicting customer churn using an Artificial Neural Network (ANN) classification model. A user-friendly web application built with Streamlit allows users to interact with the model, providing predictions based on customer data inputs.

# Table of Contents

- Project Overview

- Requirements

- Installation

- Usage

- Project Structure

- Streamlit App

- Contributing


# Project Overview

This project demonstrates how an ANN classification model can be utilized to predict customer churn based on features like account activity. The model was trained on a dataset of customer records, achieving high accuracy and robustness. The Streamlit-based web app allows easy interaction with the model.

# Features

- ANN Classification Model

- Streamlit Web App: Allows users to input customer data and get churn predictions.

- Visualization: Display of feature importance and churn probability.

# Requirements

To run this project, you need the following dependencies:

- Python 3.10+
- tensorflow
- pandas
- numpy
- scikit-learn
- tensorboard
- matplotlib
- streamlit


# Installation

- Clone the repository:
git clone https://github.com/peteralao877/churn-prediction.git
cd churn-prediction

- Create and activate a virtual environment (optional but recommended):
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

- Install dependencies:
pip install -r requirements.txt

# Usage
- Running the Streamlit App

Navigate to the project directory.

- Start the Streamlit app:

streamlit run app.py

Open the link provided in the terminal to access the app in your browser.

- Interacting with the App

Input customer details (e.g., age).

- Click on the Predict button to view churn likelihood.

# Project Structure

churn-prediction/
|— app.py               # Streamlit app script
|— model/
    |— model.h5    # Saved ANN model
|— data/
    |— Churn_Modelling.csv       # Dataset used for training and validation
|— requirements.txt    # List of dependencies


# Streamlit App

The Streamlit app provides an intuitive interface to interact with the churn prediction model. Key functionalities include:

Input forms for customer data.

Displaying churn probability and prediction.

Potential future features: data upload, visualization of customer trends.

# Contributing

Contributions are welcome! Please follow these steps:

- Fork the repository.

- Create a new branch:

git checkout -b feature-name

- Commit your changes:

git commit -m "Add some feature"

- Push to the branch:

git push origin feature-name

- Open a pull request.

