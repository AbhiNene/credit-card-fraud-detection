# credit-card-fraud-detection
Credit Card Fraud Detection
This project builds and evaluates machine learning models to detect fraudulent credit card transactions. It uses the Kaggle Credit Card Fraud Detection dataset, which contains 284,807 transactions with 492 fraud cases (highly imbalanced).

The workflow includes:

Data preprocessing: Scaling transaction amounts, removing irrelevant features, downsampling majority class for speed.

Baseline model: Logistic Regression with class balancing.

Resampling: SMOTEENN to oversample the minority class and clean noisy samples.

Advanced model: Random Forest Classifier with hyperparameter tuning via RandomizedSearchCV.

Evaluation metrics: ROC-AUC, confusion matrix, precision-recall curve, and classification report.

Key Results:

Achieved ~0.99 ROC-AUC with Random Forest + SMOTEENN.

Clear separation between fraud and non-fraud classes after resampling.

Robust performance in both balanced and imbalanced settings.

Tech stack: Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Imbalanced-learn

Dataset link: Kaggle - Credit Card Fraud Detection



