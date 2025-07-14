Traffic Congestion Predictor & Regressor

A research-based practice project for predicting traffic congestion using machine learning techniques. This project leverages both classification and regression models—Random Forest and Support Vector Regression (SVR)—to forecast congestion levels based on historical traffic data.
Table of Contents

    Overview
    Features
    Data
    Getting Started
    Modeling Approach
    Results
    Requirements
    Usage
    Contributing
    License

Overview

This repository demonstrates an end-to-end workflow for building and evaluating machine learning models to predict traffic congestion. The primary goal is to explore how classification (Random Forest) and regression (SVR) algorithms perform on real-world traffic datasets.
Features

    Data preprocessing and exploratory analysis
    Feature engineering for traffic datasets
    Classification using Random Forest
    Regression using Support Vector Regression (SVR)
    Model evaluation and comparison
    Jupyter Notebooks for step-by-step analysis

Data

The project uses publicly available traffic datasets. Details about data sources, preprocessing steps, and features are documented in the notebooks.
Getting Started

    Clone the repository:
    bash

git clone https://github.com/nyx-suk/traffic-congestion-predictor-regressor.git
cd traffic-congestion-predictor-regressor

Install dependencies:
bash

pip install -r requirements.txt

Open the notebooks: You can explore and run the analysis using Jupyter Notebook:
bash

    jupyter notebook

Modeling Approach

    Random Forest Classifier: Used to classify congestion levels (e.g., low, medium, high).
    Support Vector Regression (SVR): Used to predict continuous values related to congestion metrics.

Results

Model performance is evaluated using standard metrics such as accuracy, F1-score (for classification), and RMSE (for regression). See the results and analysis in the provided notebooks.
Requirements

    Python 3.7+
    Jupyter Notebook
    scikit-learn
    pandas
    numpy
    matplotlib
    seaborn

(See requirements.txt for details.)
Usage

    Run the Jupyter Notebooks to follow the workflow.
    Modify parameters or try different models to experiment with the data.

Contributing

Pull requests and suggestions are welcome! If you have ideas for improving the model or analysis, feel free to submit an issue or PR.
License

This project is licensed under the MIT License.
