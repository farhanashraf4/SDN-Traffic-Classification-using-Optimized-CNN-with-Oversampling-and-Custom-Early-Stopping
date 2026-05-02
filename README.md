# SDN Traffic Classification using Optimized CNN with Oversampling and Custom Early Stopping

## Overview
This project presents an optimized Convolutional Neural Network (CNN)-based system for network traffic classification in Software-Defined Networking (SDN) environments. The model leverages **37 network flow features** and handles class imbalance using Random Oversampling, while improving generalization through a custom threshold-based early stopping mechanism. Built with TensorFlow and Keras, the system achieves high classification performance with strong scalability and robustness.

## Key Features
- High-Accuracy Classification (~99.13%) using Stratified K-Fold cross-validation  
- Multi-class Traffic Classification (TCP, UDP, BENIGN)  
- Imbalance Handling with RandomOverSampler  
- Custom Early Stopping (threshold-based) to prevent overfitting  
- Robust Evaluation (Confusion Matrix, ROC, Precision-Recall, MCC)  
- Optimized Training (Batch Normalization, Dropout, Learning Rate Scheduling)  

## Repository Structure
- notebook.ipynb → CNN model training and evaluation  
- preprocessing.py → Data preprocessing (scaling, encoding)  
- requirements.txt → Dependencies  

## Dataset
- SDN Flow Dataset used for multi-class classification of network traffic (TCP, UDP, BENIGN) with imbalanced data distribution  

## Tech Stack
Python, TensorFlow, Keras, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn  

## Results
- Accuracy: ~99.13%  
- Strong performance across TCP, UDP, and BENIGN classes  
- Very low false positives with high true positive rate  
- Robust evaluation using MCC (~0.98) and ROC-AUC  

## Future Improvements
- Integrate real-time SDN controller for live traffic monitoring  
- Explore advanced architectures (LSTM, Transformer-based models)  
- Improve generalization on larger and more diverse datasets  

## Author
Farhan Ashraf  
GitHub: https://github.com/farhanashraf4  

## If you found this useful, consider giving it a star.
