# Anomaly-Dectection
Anomaly detection in engine sensor data using statistical methods and machine learning

# Ship Engine Anomaly Detection

This project demonstrates an end-to-end approach to detecting anomalies in ship engine sensor data using both statistical and machine learning methods.

## 📊 Overview

Ship engines require constant monitoring to ensure operational efficiency and safety. By identifying unusual patterns in key engine metrics, we can flag potential malfunctions before they result in costly failures.

This solution uses:
- **Interquartile Range (IQR)** for statistical outlier detection
- **One-Class SVM** and **Isolation Forest** for machine learning-based anomaly detection
- **PCA visualizations** to project anomalies in 2D space

## ⚙️ Features

- Data preprocessing and feature scaling
- Outlier detection using IQR
- Anomaly detection using:
  - One-Class SVM (with hyperparameter tuning)
  - Isolation Forest (with contamination levels from 1% to 5%)
- PCA-based 2D anomaly visualization

## 🔍 Dataset

The dataset includes six anonymized features related to engine performance:
- RPM
- Oil Pressure
- Fuel Pressure
- Coolant Pressure
- Oil Temperature
- Coolant Temperature

> 📌 *All data is anonymized and synthetic. No proprietary or sensitive client information is included.*

## 📈 Visual Output

Visualizations highlight normal vs anomalous points using color-coded PCA scatter plots.

## 🛠️ Technologies

- Python
- NumPy, Pandas
- Seaborn, Matplotlib
- Scikit-learn (SVM, Isolation Forest, PCA)

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/ship-engine-anomaly-detection.git
   cd ship-engine-anomaly-detection
