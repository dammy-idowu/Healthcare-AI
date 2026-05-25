## 🎗️ Deep Learning-Based Predictive Analytics for Automated Mammographic Breast Cancer Categorization
An end-to-end medical deep learning pipeline developed in Python using PyTorch and optimized via Optuna Bayesian hyperparameter sweeps. This project implements a stratified, class-weighted Convolutional Neural Network (CNN) using Transfer Learning (ResNet-18) to accurately categorize mammographic breast tissue images into three distinct diagnostic clinical profiles: Normal, Benign and Malignant.The primary architecture is engineered to solve a common failure point in medical image processing: **low sensitivity (recall) for malignant cases**. By integrating Stratified Dataset Splitting and Malignant Class-Weighted Cross-Entropy Loss, this model ensures critical anomalies are prioritized over standard backgrounds, establishing a robust clinical validation loop.

## 📋 Project Workflow<br>
- Introduction<br>
- Project Objective<br>
- Environmental Configuration & Dependency Initialization<br>
- Stratified Data Engineering & Preprocessing Pipelines<br>
- Model Architecture Setup, Optimization & Training<br>
- Diagnostic Performance Evaluation & Multi-Class Metrics<br>
- Inference<br>
- Recommendation

## ⚙️ Pipeline Architecture Flow
[Zipped Dataset in Google Drive]
               │
               ▼
[Clean Extraction & Sub-folder Target Re-routing]
               │
               ▼
[Stratified Dataset Splitting (70% Train / 15% Val / 15% Test)]
               │
               ▼
[Optuna Bayesian Search Loop (LR, Smoothing, Weights Optimization)]
               │
               ▼
[ResNet-18 Deep Feature Extraction -> Transfer Learning Output Layer]
               │
               ▼
[Finalized Evaluation Engine -> Evaluation Report & Simple 3x3 Matrix]

## 👨‍💻 Author
Damilola Idowu<br>
Full stack Data Analyst / Data Scientist<br>
[[[Your LinkedIn Profile Link](https://www.linkedin.com/in/damilola-idowu-contact-info)]] | damilolapeter.idowu@gmail.com

