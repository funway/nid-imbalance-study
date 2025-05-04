# NID-Imbalance-Study

This repository includes the portion of the code I was responsible for in a team project for **NYIT INCS 870**, titled:

> *"Addressing Class Imbalance in Network Intrusion Detection: A Comparative Study of Resampling Techniques and Classifier Architectures"*

This project explores how **machine learning techniques** can be applied to **Network Intrusion Detection (NID)**, particularly under the challenge of **imbalanced class distributions**.  
It compares the performance of different **data resampling methods** and **deep learning models** in detecting malicious network traffic.

---

## 📊 Dataset

The experiments in this repository are based on the **CSE-CIC-IDS2018** dataset, which includes real-world attack and benign traffic with significant class imbalance.

---

## 🔁 Workflow

This project follows a structured pipeline:

1. **Data Preprocessing**
   - Data cleaning
   - Feature scaling (e.g., StandardScaler, MinMaxScaler)

2. **Oversampling**
   - Techniques such as ROS, ADASYN, Borderline-SMOTE, and cGAN

3. **Undersampling**
   - Techniques such as RUS, NearMiss, and IHT

4. **Classification & Evaluation**
   - Models: MLP, CNN, Random Forest
   - Evaluation metrics: accuracy, precision, recall, F1-score, confusion matrix

---

## 📂 Repository Structure

