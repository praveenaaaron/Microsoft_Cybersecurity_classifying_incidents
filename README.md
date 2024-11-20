# Microsoft_Cybersecurity_classifying_incidents
A machine learning model used to classify cybersecurity incidents.


Overview

This project aims to classify cybersecurity incidents based on various features such as alert titles, incident categories, timestamps, IP addresses, and user accounts. The primary goal is to assist cybersecurity teams in quickly identifying, prioritizing, and responding to incidents based on their severity and nature.

Project Structure

data: Contains raw and processed data files.

raw: Holds the original data files.
processed: Stores cleaned and transformed data used for model training.
notebooks: Jupyter notebooks for exploratory data analysis, model training, and evaluation.

data_exploration.ipynb: Provides data exploration and visualization.
model_training.ipynb: Covers model training, tuning, and evaluation.
src: Contains the core Python scripts for data processing, training, and evaluation.

data_preprocessing.py: Handles data cleaning, feature engineering, and encoding.
model_training.py: Manages model training and hyperparameter tuning.
evaluation.py: Calculates model metrics for assessing model performance.
models: A folder to store trained models, including the final selected model.
