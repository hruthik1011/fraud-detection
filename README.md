Fraud Detection in Financial Transactions
Overview
This project focuses on detecting fraudulent transactions in credit card applications using a combination of machine learning techniques, specifically MiniSom (Self-Organizing Maps) for unsupervised learning and Artificial Neural Networks (ANN) for classification.

Features
Identifies suspicious transactions using SOM distance maps.
Classifies potential frauds with ANN.
Scalable preprocessing pipeline for handling large datasets.
Visual representation of fraud patterns.
Tools and Technologies
Programming Language: Python
Libraries: NumPy, Pandas, Matplotlib, TensorFlow, MiniSom
Visualization: Matplotlib for SOM distance maps
Preprocessing: MinMaxScaler for data normalization
Dataset
The dataset used in this project includes credit card application data with labeled instances for fraudulent and non-fraudulent transactions.

Workflow
Data Preprocessing

Normalize the dataset using MinMaxScaler.
Prepare the data for SOM and ANN training.
Unsupervised Learning with MiniSom

Train a SOM to identify the most distant nodes as potential frauds.
Visualize the results using a distance map.
Fraud Classification with ANN

Extract potential fraud cases identified by SOM.
Train an ANN on labeled data to classify transactions as fraudulent or not.
Evaluation

Evaluate the ANN using metrics such as accuracy, precision, recall, and F1-score.
Results
The project effectively identified potential fraudulent transactions using SOM.
The ANN achieved high accuracy in classifying transactions as fraudulent or legitimate.
How to Run
