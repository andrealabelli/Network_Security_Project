# Network Security Project ![DDOS](https://github.com/user-attachments/assets/de99a0e7-fd76-4200-9f58-84d23d77b36d)


This project is developed for the Network Security exam at University of Cagliari.

- Author: Andrea Labelli
- Supervisor: Prof. Marco Martalò

## Overview

This repository contains the implementation of a hybrid framework for detecting Denial of Service (DoS) and Distributed Denial of Service (DDoS) attacks in network traffic, with particular focus on IoT-oriented environments.  
The approach combines statistical traffic analysis and supervised machine learning techniques.

The project investigates:

- Statistical characterization of TCP and UDP flooding attacks  
- Comparative analysis between DoS/DDoS and other attack types  
- Supervised machine learning classification of network traffic  
- Impact of class imbalance and dataset balancing using SMOTE  

Three machine learning models are evaluated:

- Random Forest  
- Logistic Regression  
- Support Vector Machine (SVM)

## Dataset

The dataset used is the **TON_IoT_Train_Test_Network dataset**, publicly available on [Kaggle](https://www.kaggle.com/datasets/alaaelmor/ton-iot-train-test-network).

## How to run the code

1. Download the dataset from Kaggle 
2. Open Google Colab
3. Upload the dataset to Colab
4. Run the notebook sequentially

## Results

- Random Forest achieves the best overall performance
- Statistical features clearly reveal flooding behavior
- SMOTE significantly improves DoS/DDoS recall
