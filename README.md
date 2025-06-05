# 🧠 EHG-based Preterm Birth Prediction using Deep Learning

This repository contains the code and methodology for a deep learning project focused on predicting **preterm births** using **ElectroHysteroGram (EHG)** signals. This was my **second project** in a machine learning series, continuing from my previous work.

## 🩺 What is Preterm Birth?

**Preterm birth** refers to the delivery of a baby before 37 completed weeks of gestation. It is a major public health concern and one of the leading causes of **neonatal death** and **long-term health complications**. Early detection is crucial — enabling timely clinical decisions and potentially life-saving interventions.

## 🎯 Objective

To develop and evaluate a deep learning model capable of classifying **term vs. preterm deliveries** using raw EHG signals.

---

## ⚙️ Methodology

### 📊 Data Preprocessing
- Loaded and segmented raw EHG signals.
- Applied normalization for consistent input ranges.
- Encoded labels to represent term and preterm classes.

### 🎛️ Feature Extraction
- Used **Short-Time Fourier Transform (STFT)** to convert time-domain EHG signals into spectrograms for time-frequency analysis.

### 🤖 Model Architecture
- Designed a hybrid **CNN-LSTM model** to:
  - Capture spatial features from spectrograms (CNN)
  - Learn temporal dependencies in uterine contractions (LSTM)

### 🧪 Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

## 📈 Results

The final model achieved an **accuracy of over 90%**, showing strong potential for clinical applications in early detection of preterm labor.

---
