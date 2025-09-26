Logistic Regression on Wisconsin Breast Cancer Dataset :

Project Overview:
This project implements binary classification using Logistic Regression to predict whether a tumor is malignant (0) or benign (1) based on features from the Wisconsin Breast Cancer dataset.

Steps Followed :

1. Data Loading & Inspection
  * Dataset loaded from Excel/CSV.
  * Features (X) and target labels (y) separated.

2. Train/Test Split & Standardization
  * Split dataset into training (80%) and testing (20%) sets.
  * Standardized features to improve model convergence.

3. Logistic Regression Model
  * Trained on standardized features.
  * Predictions made using a sigmoid function, converting linear outputs to probabilities.

4. Evaluation Metrics
  * Confusion Matrix: shows TP, TN, FP, FN counts.
  * Precision & Recall: measure correctness of positive predictions and coverage of actual positives.
  * ROC-AUC Curve: measures model’s ability to separate classes across thresholds.

5. Threshold Tuning
  * Default threshold = 0.5

* Threshold can be adjusted to balance precision vs recall depending on application.
