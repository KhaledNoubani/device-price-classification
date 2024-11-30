Devices Price Classification System

This project implements a Devices Price Classification System using Python and Spring Boot. The system predicts and classifies the price range of devices based on their specifications and provides a RESTful API to interact with the system.

Overview:
This system helps sellers classify the price range of devices (low, medium, high, or very high cost) based on various characteristics like RAM, battery power, screen size, etc. The project has two main components:

Python Project:
        Builds and trains a Machine Learning model to predict the price range of devices.
        Evaluates the model using various metrics and visualizations.
        Prepares the dataset by scaling numerical features and encoding categorical ones.
Dataset

The dataset consists of device specifications and their corresponding price range. The columns include:

    ID: Unique identifier for the device.
    battery_power: Total battery energy (mAh).
    blue: Has Bluetooth or not (0/1).
    clock_speed: Processor speed (GHz).
    dual_sim: Has dual SIM support or not (0/1).
    ... (and more features ).


Target Variable: price_range
Values:

    0: Low cost
    1: Medium cost
    2: High cost
    3: Very high cost



Technologies Used

    Python (ML development):
        Libraries: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn



Features
Python Project

    Exploratory Data Analysis (EDA) with visualizations.
    Feature scaling and preprocessing.
    Machine Learning model training and evaluation.
    Predictions saved as a CSV file.



Usage
Python Model

    Run the Python script to train the model and save predictions.
    Test predictions are saved in test_predictions.csv.


Model Evaluation

The logistic regression model was used as the baseline. Below are the evaluation metrics:

    Accuracy: XX%
    Precision (Weighted): XX%
    Recall (Weighted): XX%
    F1 Score (Weighted): XX%

Visualization of metrics (e.g., Confusion Matrix, ROC Curve) is included in the Python script.
