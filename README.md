# 🚦 Predicting Urban Traffic Flow During Peak Hours Using ARIMA and LSTM Models

This repository presents a time-series-based solution for short-term urban traffic flow prediction using **ARIMA**, **LSTM**, and a **Hybrid ARIMA–LSTM** approach. The project focuses on forecasting during **peak hours** using real-world traffic data to support intelligent transportation systems (ITS) and smart city initiatives.

## 📘 Overview

Traffic congestion in urban areas, especially during rush hours, negatively impacts commuting efficiency and urban sustainability. This project:

* Compares classical and deep learning models for traffic forecasting
* Uses external features like weather and holidays to boost accuracy
* Evaluates model performance using **MAE**, **RMSE**, and **R²**
* Demonstrates that **LSTM** significantly outperforms ARIMA and hybrid models

## 📊 Dataset

* Source: [Metro Interstate Traffic Volume – Kaggle](https://www.kaggle.com/datasets/utkarshxy/metro-interstate-traffic-volume)
* 48,000+ hourly records including weather and calendar data
* Collected from I-94 highway in Minneapolis-St. Paul (2012–2018)

## 🛠️ Tech Stack

* Python 3.10+
* Pandas, NumPy
* Statsmodels (ARIMA)
* TensorFlow/Keras (LSTM & Hybrid)
* Scikit-learn
* Matplotlib, Seaborn

## 🚀 Quick Start

```bash
git clone https://github.com/venkatasaichalla02/traffic-flow-prediction.git
cd traffic-flow-prediction
pip install -r requirements.txt
```

Open the Jupyter Notebook in `/notebooks` and follow the workflow for preprocessing, model training, and evaluation.

## 📈 Try on Google Colab

👉 [Click here to run the project on Google Colab](https://colab.research.google.com/drive/1wirOZaPpGUbChhJ5zJXZcFYgkzta3FPr?usp=sharing)

## ✅ Results Summary

| Model  | MAE        | RMSE        | R²        |
| ------ | ---------- | ----------- | --------- |
| ARIMA  | 2880.02    | 3428.02     | -2.156    |
| LSTM   | **580.95** | **1020.39** | **0.720** |
| Hybrid | 2893.97    | 3419.91     | -2.141    |

## 🏙️ Applications

* Real-time traffic management
* Adaptive signal systems
* Smart mobility planning
* Congestion-aware navigation

## 📩 Contact

* 👨‍🎓 **Name**: Venkatasai Ganesh Challa
* 🏫 **Institution**: Dublin Business School, Ireland
* 👨‍💻 **GitHub**: [venkatasaichalla02](https://github.com/venkatasaichalla02)
* 🔗 **LinkedIn**: [venkatasai-ganesh-challa](https://www.linkedin.com/in/venkatasai-ganesh-challa-47591230a)
* 📍 **Location**: Dublin, Ireland

