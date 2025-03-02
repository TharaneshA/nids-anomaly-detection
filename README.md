# Network Intrusion Detection System with Anomaly-based Detection

## Overview
A hybrid deep learning approach for zero-day attacks, network intrusion detection using autoencoders and LSTM with attention mechanism. The system combines unsupervised and supervised learning techniques to detect network intrusions.

## Features
- Hybrid architecture (Autoencoder + LSTM + Attention mechanism)
- Anomaly detection through reconstruction error analysis
- High performance metrics (F1-Score: 0.96, AUC-ROC: 0.98)
- Comparative analysis with baseline models

## Requirements
- Python 3.8+
- TensorFlow 2.x
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn

## CICIDS 2017 Dataset

The CICIDS 2017 dataset is used in this project. Instead of uploading the dataset to GitHub due to file size constraints, you can download the dataset directly from Kaggle:

[CICIDS 2017 Full Dataset](https://www.kaggle.com/datasets/sweety18/cicids2017-full-dataset)


## Model Architecture
- Autoencoder for dimensionality reduction
- LSTM with attention for sequential pattern analysis
- Reconstruction error analysis for anomaly detection

  ![image](https://github.com/user-attachments/assets/7830452b-0345-4e4e-8625-b50ababa61c2)

## Performance
- F1-Score: 0.96
- AUC-ROC: 0.98
- Comparative analysis with RF and XGBoost baseline models

  ![image](https://github.com/user-attachments/assets/76e8c0cd-2dc0-47bc-b12f-b2564785c7fe)

## Author
Tharanesh A
