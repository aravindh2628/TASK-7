
🧠 AI & ML Internship – Task 7: Support Vector Machines (SVM)

📌 Project Title: Breast Cancer Detection using Support Vector Machines (SVM)

📋 Objective

To implement Support Vector Machines (SVM) for classifying cancer cases as benign or malignant using the Breast Cancer Dataset, and evaluate performance using different kernel functions and hyperparameters.

🛠️ Tools & Libraries

Python

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

📁 Dataset

Name: Breast Cancer Wisconsin Diagnostic Dataset

Source: UCI Machine Learning Repository

Target Variable: diagnosis (M = Malignant, B = Benign)

🚀 Steps Performed

Loaded the Dataset – Cleaned unnecessary columns and encoded target values.

Data Preprocessing – Applied normalization using StandardScaler.

Model Building – Trained:

SVM with Linear Kernel

SVM with RBF (Gaussian) Kernel

Hyperparameter Tuning – Adjusted C and gamma.

Model Evaluation – Used:

Accuracy

Confusion Matrix

Classification Report

Cross-validation

Visualization – Applied PCA to reduce to 2D and visualized decision boundary.

🔍 Results

Linear SVM Accuracy: ~97%

RBF Kernel Accuracy: ~98%

Cross-Validation Scores were also reported to check model stability.

📊 Visual Output

2D PCA-based decision boundary plot for RBF kernel

Scatter plot shows separation between benign and malignant samples

