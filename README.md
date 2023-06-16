# Anomaly-Detection-for-Network-Intrusion-Detection
Deep Autoencoder-Based Anomaly Detection for Network Intrusion Detection Uncovering Illegitimate Connections with High Precision


This project aims to develop an effective system for detecting illegitimate connections in a computer network using deep autoencoder-based anomaly detection techniques. The project successfully addresses the challenges of preprocessing and transforming the train and test datasets, handling missing values, and performing feature engineering to prepare the data for model training.

The autoencoder model is built and tuned using various architectures, including BatchNormalization and Dropout layers, which contribute to improved performance and robustness. By training the autoencoder on "normal" instances, the model learns to reconstruct normal connections and identify anomalies based on the differences between the reconstructed and original data.

The model's performance is evaluated using multiple metrics, including mean squared error (MSE), receiver operating characteristic (ROC), area under the curve (AUC), accuracy, and Cohen's Kappa. Through careful parameter tuning and model optimization, a target AUC of 0.99 is achieved, demonstrating the high precision and reliability of the developed system.

In the github repository, you will find the complete code implementation, along with detailed explanations of the data preprocessing steps, model architecture, and evaluation metrics. The repository showcases strong skills in data preprocessing, modeling, and evaluation, highlighting the effectiveness of the fraud detection system for computer networks.

By leveraging deep autoencoder-based anomaly detection, this project provides a valuable solution for network intrusion detection, enabling organizations to uncover illegitimate connections with high precision. The developed system can be further expanded and integrated into existing network security frameworks to enhance overall cybersecurity measures.





