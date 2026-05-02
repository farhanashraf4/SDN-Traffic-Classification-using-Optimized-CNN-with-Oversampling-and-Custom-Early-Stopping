# Optimized CNN-Based Network Traffic Classification for SDN

High-Performance Network Traffic Classification using Deep Learning, Oversampling, and Custom Early Stopping

## Overview
This project presents an optimized Convolutional Neural Network (CNN)-based system for network traffic classification in Software-Defined Networking (SDN) environments. It handles class imbalance using Random Oversampling and improves model generalization through a custom early stopping mechanism. Built with TensorFlow and Keras, the system achieves near-perfect classification performance with strong scalability and robustness.

## Key Features
- High-Accuracy Classification (~99–100%) using Stratified K-Fold cross-validation  
- Imbalance Handling with RandomOverSampler (TCP, UDP, BENIGN)  
- Custom Early Stopping (threshold-based) to prevent overfitting  
- Robust Evaluation (Confusion Matrix, ROC, Precision-Recall, MCC)  
- Optimized Training (Batch Normalization, Dropout, Learning Rate Scheduling)  

## Repository Structure
- notebook.ipynb → CNN model training & evaluation  
- preprocessing.py → Data preprocessing (scaling, encoding)  
- requirements.txt → Dependencies  

## Dataset
- SDN Flow Dataset for multi-class traffic classification (TCP, UDP, BENIGN) with imbalanced data scenarios  

## Tech Stack
Python, TensorFlow, Keras, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn  

## Results
- Accuracy: ~99–100%  
- Very low false positives, high true positives  
- Strong MCC and ROC-AUC performance  

## Future Improvements
- Real-time deployment for live traffic monitoring  
- Explore LSTM / Transformer-based models  
- Improve generalization on larger datasets  

## Author
Farhan Ashraf  
GitHub: https://github.com/farhanashraf4  

## If you found this useful, consider giving it a star.
