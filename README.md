# Credit-Card-Fraud-ML-

Project Overview
This project aims to build a machine learning model to detect fraudulent credit card transactions. Given the highly imbalanced nature of the dataset, special techniques are applied to ensure the model effectively identifies fraudulent transactions while minimizing false positives.

Problem Statement
Credit card fraud is a significant issue affecting financial institutions and consumers worldwide. The challenge is to develop an accurate and reliable system to detect fraudulent transactions in real-time, preventing financial losses and protecting users' information. Due to the imbalanced nature of fraud detection datasets (with a much smaller number of fraudulent transactions compared to legitimate ones), traditional modeling techniques often fail to perform well. Thus, this project addresses this challenge by using advanced machine learning and data balancing techniques.

Real-World Use Case
In a real-world scenario, a financial institution can integrate this model into their transaction processing system. As transactions are processed, the model will flag suspicious transactions for further review by the fraud detection team. This helps in:

Reducing financial losses due to fraud.
Enhancing customer trust by securing their transactions.
Streamlining the fraud detection process, making it more efficient.
Data
The dataset used for this project is highly imbalanced, containing a large number of legitimate transactions and a small number of fraudulent transactions. Each transaction is characterized by various features derived from the original data using PCA for confidentiality.

Approach
Data Preprocessing: Cleaning and preparing the data for modeling.
Handling Imbalance: Using techniques like SMOTE (Synthetic Minority Over-sampling Technique) to balance the dataset.
Model Training: Training various models including ensemble methods.
Evaluation: Evaluating model performance using metrics such as precision, recall, F1-score, and ROC-AUC.
Optimization: Fine-tuning the models to improve performance.
Models and Techniques
RandomForestClassifier: An ensemble method using bagging.
Gradient Boosting: Boosting technique to improve performance sequentially.
XGBoost: Efficient and scalable implementation of gradient boosting.
LightGBM: Known for its speed and efficiency.
CatBoost: Handles categorical features automatically and efficiently.
Stacking: Combining predictions from multiple models for improved performance.
