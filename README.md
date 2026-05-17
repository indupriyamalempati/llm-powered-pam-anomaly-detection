# LLM-Powered Privileged Session Analysis

## Overview
This project implements a hybrid cybersecurity anomaly detection pipeline for Privileged Access Management (PAM) environments using Machine Learning and simulated LLM-based risk classification.

The system combines:
- Isolation Forest
- One-Class SVM
- SSH anomaly detection
- Privileged shell command analysis
- Simulated LLM risk scoring

## Features
- Unsupervised anomaly detection
- SSH attack detection
- Privileged session monitoring
- Command risk classification
- Automated session termination logic
- Visualization of anomalies and risk levels

## Datasets
- UCI Shell Commands Dataset
- Kaggle SSH Anomaly Dataset

## Technologies Used
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Results
### Isolation Forest
- Used as anomaly filter for PAM logs

### One-Class SVM
- Precision: 0.995
- Recall: 1.000
- F1-score: 0.997

## Research Paper
The full research paper is included in this repository.

## Author
Indu Priya Malempati
M.Eng Cybersecurity
University of Maryland.
