# Fraud Detection System using Machine Learning & Deep Learning

## Project Overview

This project implements a **Fraud Detection System** using **Machine Learning, Deep Learning, and Data Analytics**. The goal is to detect fraudulent credit card transactions with high accuracy while handling imbalanced data problems.

It uses the **Kaggle Credit Card Fraud Detection dataset** and supports an **interactive Streamlit dashboard** for visualization and monitoring.

---

## 🛠 Features

* **Handles imbalanced data** using **SMOTE (Synthetic Minority Oversampling Technique)**
*  **Machine Learning models**: Random Forest, Isolation Forest
*  **Deep Learning models**: Neural Networks with TensorFlow/Keras
*  **Real-time visualization** using `plotly`
*  **Graph-based fraud analysis** with `networkx`
*  **Interactive dashboard** using Streamlit
*  **Ngrok integration** for sharing the dashboard online

---

##  Project Structure

```
 Fraud-Detection-Project
 ┣  notebook.ipynb        # Main Jupyter notebook
 ┣  requirements.txt      # Dependencies
 ┣  README.md             # Project documentation
 ┣  app.py                # Streamlit app (if exported)
 ┗  data                  # Dataset (auto-downloaded from Kaggle)
```

---

## Dataset

* **Source:** [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
* **Size:** 284,807 transactions
* **Fraudulent cases:** 492 (0.172% of total)
* **Challenge:** Highly imbalanced dataset

---


##  Results & Insights

* Achieved **high recall** for fraud detection using **SMOTE + RandomForest**
* Neural Network model further improves classification with better generalization
* Visualizations highlight **fraudulent clusters** in transaction networks

---

## Future Enhancements

* Add **real-time fraud detection** with streaming data (Kafka/Spark)
* Implement **Explainable AI (XAI)** for fraud reasoning
* Deploy dashboard on **cloud platforms** (AWS/GCP/Heroku)
* Integrate with **blockchain-based security** for transaction logging

