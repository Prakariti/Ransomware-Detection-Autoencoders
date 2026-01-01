# Ransomware Detection Using Autoencoders

## Overview
This project implements an unsupervised ransomware detection system using autoencoders.
The model learns normal system behavior and detects ransomware-like activity as anomalies
based on reconstruction error.

## Motivation
- Ransomware data is often unlabeled
- Traditional supervised models fail in real-world scenarios
- Autoencoders are effective for anomaly detection

## Workflow
1. Data preprocessing and feature scaling
2. Train / validation / test split
3. Autoencoder training
4. Reconstruction error computation
5. Threshold selection (percentile-based)
6. Anomaly detection and visualization

## Evaluation
This is an **unsupervised learning project**.
Traditional metrics such as accuracy, precision, recall, and F1-score are **not applicable**
without ground-truth labels.

Evaluation is performed using:
- Reconstruction error distribution
- Threshold-based anomaly detection
- Visual analysis

## Technologies Used
- Python
- TensorFlow / Keras
- NumPy, Pandas
- Scikit-learn
- Matplotlib

## Future Improvements
- Evaluate on labeled datasets
- Use LSTM autoencoders
- Combine with supervised classifiers
