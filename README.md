Bank Fraud Prediction Using Machine Learning
Overview
This project aims to predict fraudulent bank transactions using machine learning techniques, specifically Random Forest, Support Vector Machine (SVM), and XGBoost. The dataset contains highly imbalanced data, where fraudulent transactions are much less frequent than legitimate ones. The project involves handling this imbalance, performing feature selection, and hyperparameter tuning using Bayesian optimization to optimize the model's performance.

Key Features
Data Preprocessing: Cleaning and handling missing values, imbalanced data.
Feature Selection: Selecting important features for model performance.
Modeling: Implementing and tuning Random Forest, SVM, and XGBoost models to predict fraudulent transactions.
Evaluation: Using performance metrics like Accuracy, Precision, Recall, and F1-Score to evaluate the model's performance.
Technologies Used
Python: Programming language used for data analysis and modeling.
Pandas & Numpy: For data manipulation and numerical calculations.
Scikit-learn: For machine learning algorithms and evaluation metrics.
XGBoost: For implementing the XGBoost model.
Matplotlib & Seaborn: For data visualization.
Hyperopt: For Bayesian optimization and hyperparameter tuning.

Team Members

Yifeng Chen
Adesina Adeniran
Kaushiki Priya Tiwary
Omar Alwehaib


Hyperparameter Tuning
The project uses Bayesian optimization via the Hyperopt library for hyperparameter tuning. You can modify the parameter space for the models based on your requirements for further optimization.

Feature Selection
Various techniques such as Recursive Feature Elimination (RFE) and Feature Importance from Random Forest are employed to select the most significant features for the model.

Performance Metrics
Accuracy: The overall correctness of the model.
Precision: The proportion of positive predictions that are actually correct.
Recall: The proportion of actual positives that were correctly identified by the model.
F1-Score: The harmonic mean of precision and recall.
Results
The models are evaluated based on the above metrics, and the best performing model is selected for deployment.

Future Work
Experiment with other algorithms for fraud detection.
Implement undersampling and oversampling techniques to handle class imbalance further.
Explore ensemble methods to improve prediction accuracy.
License
This project is licensed under the MIT License - see the LICENSE file for details.

