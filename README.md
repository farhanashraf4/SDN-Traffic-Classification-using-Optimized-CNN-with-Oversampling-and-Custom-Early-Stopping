# Optimized CNN-Based Network Traffic Classification for Software-Defined Networks

## Overview
This project presents an optimized Convolutional Neural Network (CNN)-based system for network traffic classification in Software-Defined Networking (SDN) environments. The model leverages **37 network flow features** and addresses class imbalance using Random Oversampling. A custom threshold-based early stopping mechanism is applied to improve model generalization and prevent overfitting. Built using TensorFlow and Keras, the system demonstrates high performance, scalability, and robustness.

## Key Features
- High-accuracy classification (~99.13%) using Stratified K-Fold cross-validation  
- Multi-class traffic classification (TCP, UDP, BENIGN)  
- Class imbalance handling using RandomOverSampler  
- Custom threshold-based early stopping for improved training stability  
- Comprehensive evaluation using confusion matrix, ROC curves, precision-recall analysis, and MCC  
- Optimized training with batch normalization, dropout, and learning rate scheduling  

## Repository Structure
- `notebook.ipynb` → CNN model training and evaluation  
- `preprocessing.py` → Data preprocessing (scaling, encoding)  
- `requirements.txt` → Project dependencies  

## Dataset
- SDN Flow Dataset used for multi-class classification of network traffic (TCP, UDP, BENIGN) with imbalanced data distribution  

## Tech Stack
Python, TensorFlow, Keras, Scikit-learn, Pandas, NumPy, Matplotlib, Seaborn  

## Results
- Accuracy: ~99.13%  
- Strong performance across TCP, UDP, and BENIGN classes  
- Low false positives with high true positive rate  
- Robust evaluation using MCC (~0.98) and ROC-AUC  

## Future Improvements
- Integrate real-time SDN controller for live traffic monitoring  
- Explore advanced architectures (LSTM, Transformer-based models)  
- Improve generalization on larger and more diverse datasets  

## Author
Farhan Ashraf  
GitHub: https://github.com/farhanashraf4  

## Support
If you found this project useful, consider giving it a star.
