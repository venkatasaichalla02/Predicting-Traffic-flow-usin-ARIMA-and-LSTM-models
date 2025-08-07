# 🚦 Predicting Urban Traffic Flow During Peak Hours Using ARIMA and LSTM Models

This repository contains a time-series traffic forecasting project that compares the performance of ARIMA, LSTM, and Hybrid ARIMA–LSTM models. The focus is on short-term traffic volume prediction during **peak hours** using the **Metro Interstate Traffic Volume** dataset from Kaggle. This project supports the development of **Intelligent Transportation Systems (ITS)** and smart city applications.

## 📘 Overview

Urban traffic congestion during rush hours significantly impacts travel time, fuel consumption, and quality of life. This project explores:

* The capabilities of **ARIMA** for modeling linear patterns
* The strength of **LSTM** in capturing nonlinear dependencies
* The potential of a **hybrid model** combining both approaches
* How **weather and temporal variables** influence prediction accuracy

The LSTM model showed the best performance (R² ≈ 0.72), outperforming ARIMA and hybrid models in forecasting high-variance traffic patterns.

## 📊 Dataset

I used the [Metro Interstate Traffic Volume dataset](https://www.kaggle.com/datasets/utkarshxy/metro-interstate-traffic-volume), which includes:

* Hourly traffic volume
* Weather data (temperature, rain, snow, etc.)
* Time-based indicators (hour, day, month, holiday, etc.)
* 48,000+ observations from 2012–2018

## 🛠️ Tech Stack

* Python 3.10+
* Pandas, NumPy – Data wrangling
* Matplotlib, Seaborn – Visualizations
* Statsmodels – ARIMA implementation
* TensorFlow / Keras – LSTM & Hybrid model
* Scikit-learn – Evaluation metrics, preprocessing

## ⚙️ Project Structure

```
├── data/                 # Raw and processed datasets
├── notebooks/            # Jupyter notebooks for EDA and modeling
├── models/               # Saved model artifacts (optional)
├── results/              # Forecast plots and metrics
├── requirements.txt      # Python dependencies
└── README.md             # Project description
```

## 🚀 Quick Start

1. **Clone the repository**

```bash
git clone https://github.com/yourusername/traffic-flow-prediction.git
cd traffic-flow-prediction
```

2. **Install dependencies**

```bash
pip install -r requirements.txt
```

3. **Run the notebook**
   Open the main Jupyter Notebook in the `/notebooks` folder and follow step-by-step modeling and analysis.

## 📈 Try on Google Colab

You can try the full LSTM model in your browser without setup:
👉 [Open in Colab](https://colab.research.google.com/) *(link here if you upload your notebook)*

## ✅ Key Results

| Model  | MAE        | RMSE        | R²        |
| ------ | ---------- | ----------- | --------- |
| ARIMA  | 2880.02    | 3428.02     | -2.156    |
| LSTM   | **580.95** | **1020.39** | **0.720** |
| Hybrid | 2893.97    | 3419.91     | -2.141    |

---

## 🏙️ Applications

* Adaptive traffic signals
* Navigation tools with live congestion predictions
* Smart city infrastructure planning
* Public transport scheduling optimization

## 📩 Contact

**Author:** Venkatasai Ganesh Challa
**Email:www.linkedin.com/in/venkatasai-ganesh-challa-47591230a
**Location:** Dublin, Ireland

---

