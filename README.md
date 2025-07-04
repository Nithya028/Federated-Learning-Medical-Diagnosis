# Federated-Learning-Medical-Diagnosis

This project implements a privacy-preserving Federated Learning (FL) system for binary medical classification (e.g., diabetes prediction). Using PyTorch and the Flower framework, it simulates multiple clients collaboratively training a shared neural network model on local data without transferring sensitive patient information.
## 🗂 Repository Structure
Federated-Learning-Medical-Diagnosis/
├── data/
│   └── diabetes.csv              # PIMA Diabetes Dataset
├── centralized_model.py         # Baseline centralized training script
├── flwr_client.py               # Federated client implementation
├── flwr_server.py               # Federated server setup
├── secure_aggregation.py        # (Optional) Secure aggregation simulation
├── utils.py                     # Shared utility functions (data loading etc.)
├── requirements.txt             # Python dependencies
└── README.md                    # Project documentation
## 🧪 Project Overview

Traditional machine learning centralizes data, risking privacy violations. Federated Learning avoids this by training models locally on edge devices or institutions (e.g., hospitals), sharing only model updates with a central server.

This project uses the PIMA Indians Diabetes Dataset to train a binary classifier across simulated FL clients and compares the accuracy of federated vs. centralized training.

---

## 📊 Dataset

- Name: PIMA Indians Diabetes Dataset  
- Source: Kaggle – https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset  
- Description: Medical diagnostic features for predicting diabetes occurrence.  
- Format: CSV with features like Glucose, Blood Pressure, Age, BMI, etc.

