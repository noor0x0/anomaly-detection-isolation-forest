# Anomaly Detection Using Isolation Forest

## Overview
This project applies unsupervised machine learning to detect anomalies in real-world datasets using the Isolation Forest algorithm.  
The project focuses on detecting unusual patterns in credit card transactions and IoT sensor readings.

## Datasets
The project uses two datasets:
- Credit Card Fraud Detection Dataset
- IoT Sensor Dataset

Dataset summary:
- Credit Card Dataset: 284,807 records and 30 features
- IoT Dataset: 3,000 records and 5 features

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- PCA Visualization
- Isolation Forest
- Local Outlier Factor

## Methodology
The main steps include:
1. Loading the datasets
2. Data preprocessing
3. Feature scaling using StandardScaler
4. Training Isolation Forest
5. Predicting anomalies
6. Visualizing anomaly behavior using PCA
7. Comparing Isolation Forest with Local Outlier Factor

## Model
The main model used is Isolation Forest:

```python
IsolationForest(contamination=0.01, random_state=42)
```
## Results

Isolation Forest successfully detected anomalies in both datasets.
It showed strong scalability and speed compared to Local Outlier Factor.

## Runtime comparison:

Isolation Forest: around 3 seconds
Local Outlier Factor: around 244 seconds

## Project Files
anomaly-detection-isolation-forest/
├── README.md
├── anomaly_detection_isolation_forest.ipynb
├── report/
├── presentation/
└── requirements.txt

## Author

Noor Mamoun
IT / AI Student
The Hashemite University
