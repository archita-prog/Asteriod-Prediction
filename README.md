Project Overview
Trained an XGBoost Classifier to predict asteroid hazards.
Performed feature engineering and data preprocessing on NASA’s asteroid dataset.
Evaluated model performance using accuracy, precision, recall, and F1-score.

Dataset
Source: '/kaggle/input/nasa-asteroids-classification/nasa.csv' (from Kaggle).

Features:
Orbital parameters (e.g., semi-major axis, eccentricity).
Physical properties (e.g., diameter, albedo).
Close-approach data (e.g., relative velocity, miss distance).
Target Variable: Hazardous (Binary: True or False).

Exploratory Data Analysis (EDA)
Analyzed missing values and outliers.
Visualized feature distributions (histograms, box plots).
Checked class imbalance in hazardous vs. non-hazardous asteroids.
Studied correlations between features.

Machine Learning Approach
XGBoost Classifier
Optimized hyperparameters learning_rate, max_depth, n_estimators.

Evaluated using:
Confusion Matrix
ROC-AUC Curve

Classification Report Precision, Recall, F1-Score.
               Precision    Recall   F1-Score  Support
           0       1.00      1.00      1.00      1181
           1       0.99      0.99      0.99       226
          
    accuracy                           1.00      1407
   macro avg       0.99      0.99      0.99      1407
weighted avg       1.00      1.00      1.00      1407



🚀 Results
Achieved 99.64% accuracy.

