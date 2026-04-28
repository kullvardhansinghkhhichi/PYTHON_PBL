Project Title: Credit Card Default Prediction (Phase 2)

Description: This project focuses on predicting whether a credit card
client will default on their payment next month. It uses machine
learning techniques including data preprocessing, dimensionality
reduction (PCA), and classification models.

Dataset: - File: default of credit card clients.csv - The dataset
contains customer demographic data, credit history, and payment
behavior. - Target Variable: “default payment next month” (renamed to
“target”)

Steps Performed:

1.  Data Loading:
    -   Dataset is loaded using pandas.
    -   Unnecessary column “ID” is removed.
2.  Data Preprocessing:
    -   Column renamed: “default payment next month” → “target”
    -   Missing values handled using median imputation for:
        -   EDUCATION
        -   MARRIAGE
        -   PAY_0
3.  Feature Scaling:
    -   StandardScaler is used to normalize feature values.
4.  Train-Test Split:
    -   Dataset is divided into training and testing sets.
5.  Dimensionality Reduction:
    -   PCA (Principal Component Analysis) is applied.
    -   95% variance is retained to reduce feature dimensions.
6.  Models Used:
    -   Support Vector Machine (SVM)
    -   K-Nearest Neighbors (KNN)
7.  Model Evaluation:
    -   Accuracy Score
    -   Classification Report
    -   ROC-AUC Score
    -   ROC Curve visualization
8.  Visualization:
    -   Matplotlib and Seaborn are used for plotting performance
        metrics.

Requirements: - Python 3.x - pandas - numpy - matplotlib - seaborn -
scikit-learn

How to Run: 1. Place the dataset file in the correct directory. 2.
Update the file path in the code if necessary. 3. Run the notebook
step-by-step. 4. Ensure all required libraries are installed.

Notes: - Make sure the dataset path is correct (currently set as a local
Windows path). - PCA reduces computation time and improves model
efficiency. - Results may vary depending on train-test split.

Author: Shivank Mahajan
