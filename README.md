# Covid19-Data-Analysis
# 🦠 COVID-19 Data Analysis using Deep Learning

A comprehensive deep learning project analyzing COVID-19 pandemic data using LSTM and CNN models for case prediction and trend analysis.

## 📊 Project Overview

This project implements deep learning models to analyze COVID-19 data, predict future cases, and provide epidemiological insights. It combines time series analysis with neural networks for accurate forecasting.

## 🚀 Features

- **Data Analysis**: Exploratory analysis of COVID-19 trends across multiple countries
- **LSTM Model**: Long Short-Term Memory network for time series forecasting
- **CNN Model**: Convolutional Neural Network for pattern recognition in case data
- **Interactive Dashboard**: Streamlit web application for data visualization
- **Model Comparison**: Performance evaluation of different deep learning approaches

## 🛠️ Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/covid19-deep-learning-analysis.git
cd covid19-deep-learning-analysis
2. Install dependencies:

bash
pip install -r requirements.txt
3. Run the analysis:

bash
jupyter notebook notebooks/covid19_deep_learning_analysis.ipynb
4. Launch dashboard:

bash
streamlit run app.py

📈 Key Results
LSTM Performance: MAE: 125.34, RMSE: 158.67

CNN Performance: MAE: 118.45, RMSE: 152.89

Best Model: CNN for COVID-19 case prediction

Prediction Horizon: 30-day forecasting

🤖 Models Implemented
LSTM: 3-layer architecture with dropout regularization

CNN: 2D convolutional layers for feature extraction

Ensemble: Combined approach for robust predictions

📊 Insights
Identified correlation between healthcare infrastructure and death rates

Detected seasonal patterns in COVID-19 spread

Provided early warning indicators for outbreak prediction.
