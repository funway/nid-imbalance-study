# NID-Imbalance-Study

**Addressing Class Imbalance in Network Intrusion Detection**  
*A Comparative Study of Resampling Techniques and Classifier Architectures*

---

## 📘 Project Description

This repository includes the portion of the code I was responsible for in a team project for **NYIT INCS 870**, titled:

> *"Addressing Class Imbalance in Network Intrusion Detection: A Comparative Study of Resampling Techniques and Classifier Architectures"*

The project focuses on addressing **class imbalance** in **Network Intrusion Detection (NID)** and comparing the performance of different **resampling techniques** and **classifier architectures**.

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

