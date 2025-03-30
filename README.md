# SmartBot Marketplace Model Demo

This repository contains a sample notebook and test input files to demonstrate the usage of **SmartBot**, an Emotion-Aware Sentiment Classifier built for FinServ Contact Centers.

## 🧪 What It Does
SmartBot analyzes preprocessed audio features and returns a real-time emotion label such as `"happy"`, `"sad"`, `"angry"`, or `"neutral"` using a SageMaker-hosted endpoint.

## 📓 Demo Notebook
Open and run `SmartBot-RealTime-Sentiment-API-Demo.ipynb` to:
- Connect to your SageMaker endpoint
- Send sample input features
- View emotion predictions in real-time

## 📂 File Structure
smartbot-marketplace-demo/
├── SmartBot-Demo-Notebook.ipynb      
├── test-inputs/
│   └── test-1.json                   
├── README.md                         
└── LICENSE                           


## ✅ Requirements
- AWS account with SageMaker endpoint deployed
- Python SDK: `boto3`, `json`
