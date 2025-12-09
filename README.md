# Credit Card Anomaly Detection Using Unsupervised Machine Learning

# Project Overview
This project implements a high-performance anomaly detection system designed to identify fraudulent and suspicious credit card transactions using unsupervised machine learning. Since fraud datasets are extremely imbalanced and often unlabeled, the model learns normal transaction behavior and flags abnormalities automatically.

# Problem Statement
Credit card fraud causes massive financial losses globally. Traditional supervised models require labeled fraud data, which is limited and expensive. This project solves that problem using unsupervised learning to detect abnormal behavior without prior fraud labels.

# Project Objective
- Detect abnormal and fraudulent transactions without labeled data
- Handle highly imbalanced financial datasets
- Provide interpretable visualizations of detected anomalies
- Build a system suitable for real-world banking and fintech use

# Dataset
- Real-world credit card transaction dataset
- Highly imbalanced distribution between normal and fraudulent transactions
- Dataset preprocessing includes:
  - Feature scaling
  - Noise handling
  - Dimensionality reduction

# System Workflow
- Load and explore the dataset
- Apply feature scaling and preprocessing
- Train the Isolation Forest anomaly detection model
- Generate anomaly scores for each transaction
- Classify transactions as normal or anomalous
- Apply PCA and t-SNE for visual interpretation
- Analyze fraud separation and detection performance

# Visual Outputs
- Anomaly score distribution plot
- PCA visualization of anomalies
- t-SNE clustering of transactions
- Outlier detection graphs

# Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

# Results
- Successful detection of anomalous transactions
- Strong separation between normal and fraudulent behavior
- High effectiveness on highly imbalanced financial data
- Model suitable for real-time fraud detection systems

# Real-World Applications
- Credit card fraud detection
- Online payment security
- Banking transaction monitoring
- Financial risk management
- Cybersecurity in fintech systems

# Skills Demonstrated
- Unsupervised machine learning
- Anomaly detection systems
- Financial data analysis
- Feature scaling and preprocessing
- Dimensionality reduction
- Data visualization
- Model evaluation on imbalanced datasets
