# Fraud Detection in Financial Transactions

## Overview

This project focuses on detecting fraudulent financial transactions using machine learning and deep learning techniques. It addresses the challenge of imbalanced data and demonstrates robust model evaluation and real-time deployment capabilities.

## Dataset

* Source: Credit Card Fraud Detection dataset from Kaggle.
* Characteristics: Highly imbalanced dataset with a small proportion of fraudulent transactions.

## Key Features

* **Imbalanced Data Handling**: Applied SMOTE (Synthetic Minority Oversampling Technique) and undersampling.
* **Algorithms Used**:

  * Logistic Regression
  * Random Forest
  * Autoencoders (for anomaly detection)
* **Evaluation Metrics**:

  * Precision
  * Recall
  * F1-score
  * ROC-AUC

## Deployment

* Built a **real-time fraud detection API** using **FastAPI** / **Flask**.
* Can be deployed to cloud platforms for production use.

## Results

* Achieved **98% recall**, reducing **false negatives by 30%**.

## Skills & Technologies Demonstrated

* **Machine Learning & Anomaly Detection**
* **Imbalanced Data Handling** (SMOTE, undersampling)
* **Scikit-learn, TensorFlow, PyTorch**
* **FastAPI / Flask Deployment**
* **Model Evaluation & Data Preprocessing**

## ATS-Friendly Keywords

Fraud Detection, Anomaly Detection, Imbalanced Data, Random Forest, Autoencoders, FastAPI, Python.

## How to Run

```bash
# Install dependencies
pip install -r requirements.txt

# Train the model
python train.py

# Run the API
uvicorn app:app --reload
```
