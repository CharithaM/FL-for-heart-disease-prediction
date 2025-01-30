Federated Learning for Heart Disease Prediction

Overview

This project applies Federated Learning (FL) to heart disease prediction using the FLWR (Flower) framework. Federated Learning enables decentralized training of machine learning models without sharing raw data, ensuring privacy and security. The model is trained across multiple simulated clients using the FedAvg (Federated Averaging) strategy.

Features

Privacy-Preserving Model Training: Uses federated learning to keep sensitive health data on local devices.

Decentralized Training: Data remains distributed across multiple simulated clients.

Federated Averaging: Aggregates model updates from clients without exchanging raw data.

Heart Disease Prediction: Utilizes patient health data to predict the likelihood of heart disease.

Dataset

The dataset used includes the following features:

age, sex, cp, trestbps, chol, fbs, restecg, thalach, exang, oldpeak, slope, ca, thal, target

The target column indicates whether a patient has heart disease (1) or not (0).

Technologies Used

Python

FLWR (Flower Framework)

TensorFlow/PyTorch (for model training)

NumPy & Pandas (data processing)

Scikit-learn (data preprocessing and evaluation)

Installation

Clone the repository:

git clone https://github.com/your-username/federated-heart-disease.git
cd federated-heart-disease

Install dependencies:

pip install -r requirements.txt

Usage

Start the FL server:

python server.py

Start FL clients (in separate terminals):

python client.py

Monitor training logs to track model performance.

Model Training Process

