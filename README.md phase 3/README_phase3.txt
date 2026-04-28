Project Title: Credit Card Default Prediction (Phase 3)

Description: This phase extends the credit card default prediction
project by improving model performance, applying advanced techniques,
and conducting deeper evaluation.

Dataset: - File: default of credit card clients.csv - Contains customer
demographic, financial, and repayment history. - Target Variable:
“default payment next month” (renamed to “target”)

Steps Performed:

1.  Data Preprocessing:
    -   Cleaning and handling missing values
    -   Feature encoding and transformation
    -   Feature scaling using StandardScaler
2.  Feature Engineering:
    -   Creation of new meaningful features (if applicable)
    -   Selection of important features
3.  Dimensionality Reduction:
    -   PCA applied to reduce dimensionality while preserving variance
4.  Model Building:
    -   Multiple models implemented such as:
        -   Support Vector Machine (SVM)
        -   K-Nearest Neighbors (KNN)
        -   (Optional) Logistic Regression / Random Forest / other
            models
5.  Hyperparameter Tuning:
    -   Optimization using GridSearchCV or similar techniques
6.  Model Evaluation:
    -   Accuracy Score
    -   Classification Report
    -   ROC-AUC Score
    -   Confusion Matrix
    -   ROC Curve visualization
7.  Performance Comparison:
    -   Comparison of different models to select the best one
8.  Visualization:
    -   Graphical representation of model performance using matplotlib
        and seaborn

Requirements: - Python 3.x - pandas - numpy - matplotlib - seaborn -
scikit-learn

How to Run: 1. Ensure dataset file is available in the correct
directory. 2. Update dataset path if required. 3. Run the notebook
step-by-step. 4. Install required libraries if missing.

Notes: - Proper preprocessing is crucial for model performance. - PCA
helps in reducing overfitting and computation time. - Hyperparameter
tuning improves model accuracy.

Author: Shivank Mahajan
