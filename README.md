# Federated-Learning-Medical-Diagnosis

This project implements a privacy-preserving Federated Learning (FL) system for binary medical classification (e.g., diabetes prediction). Using PyTorch and the Flower framework, it simulates multiple clients collaboratively training a shared neural network model on local data without transferring sensitive patient information.
## 🗂 Repository Structure
Federated-Learning-Medical-Diagnosis/
├── data/
│ └── diabetes.csv # PIMA Diabetes Dataset
├── centralized_model.py # Baseline centralized training script
├── flwr_client.py # Federated client implementation
├── flwr_server.py # Federated server setup
├── secure_aggregation.py # (Optional) Secure aggregation simulation
├── utils.py # Shared utility functions (data loading etc.)
├── requirements.txt # Python dependencies
└── README.md # Project documentation
