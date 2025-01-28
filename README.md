# Microsoft: Classifying Cybersecurity Incidents with Machine Learning

## Problem Statement
Develop a machine learning model capable of accurately predicting the triage grade of cybersecurity incidents based on historical evidence and customer responses. The solution aims to:
- Automate the triage process in SOCs.
- Enable guided response systems to mitigate potential threats effectively.
- Enhance enterprise security management by reducing false positives and ensuring prompt action on real threats.

## Domain
Cybersecurity and Machine Learning

## Skills Acquired
- **Data Preprocessing**
- **Machine Learning Classification Techniques**
- **Model Evaluation Metrics**: Macro-F1 Score, Precision, Recall
- **Handling Imbalanced Datasets**

## Tools and Technologies
- **Programming Language**: Python
- **Libraries**: Pandas, NumPy, Scikit-learn, XGBoost, SHAP
- **Visualization**: Matplotlib, Seaborn
- **Dataset**: GUIDE dataset (`train.csv`, `test.csv`)

## Approach

### 1. Data Exploration and Understanding
- Load and inspect the `train.csv` dataset. Perform Exploratory Data Analysis (EDA) to identify patterns, correlations, and anomalies.Address class imbalances.

### 2. Data Preprocessing
- Handle missing values using imputation or removal.Perform feature engineering, including timestamp-based features.Encode categorical variables using one-hot encoding or label encoding.

### 3. Data Splitting
- Split the data into training and validation sets using stratified sampling to maintain class distribution.

### 4. Model Selection and Training
- Establish a baseline with simple models (e.g., Logistic Regression).Experiment with advanced models like Random Forest, XGBoost, and Neural Networks.Use cross-validation for reliable performance estimation.

### 5. Model Evaluation and Tuning
- Evaluate models using **Macro-F1 Score**, **Precision**, and **Recall**.Address class imbalances using SMOTE or adjusting class weights.Perform hyperparameter tuning to optimize model performance.

### 6. Final Evaluation on Test Set
- Test the finalized model on `test.csv` and report evaluation metrics.Compare performance with the baseline model.

## Developed by:
B.N.Piraviena



