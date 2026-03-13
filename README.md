
# 📊 Stock Price Prediction Web App

[![Live App](https://img.shields.io/badge/🚀%20Launch%20App-Streamlit-green?style=for-the-badge)](https://stock-price-prediction-hybridmodel.streamlit.app/)
[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=fff)](#)

## 🌐 Live App

👉 Access the deployed app here: [Stock Price Prediction Dashboard](https://stock-price-prediction-hybridmodel.streamlit.app/)


## 📈 Project Overview

**Project Title:** Cracking the Market Code with AI-Driven Stock Price Prediction using Time Series Analysis

Stock market forecasting is a complex challenge due to its inherent volatility and unpredictability. Traditional statistical models often fail to capture hidden patterns in stock price movements. This project addresses the issue by leveraging machine learning models to:

- Predict the **next day's closing price** (Regression)
- Predict the **direction of the stock price movement (Up/Down)** (Classification)

This tool serves as a decision support system for analysts and traders, using historical and technical indicators to generate informed predictions.

---

## 🎯 Objectives

- **Predict Future Prices:** Develop regression models (Random Forest, Linear Regression) to forecast next-day closing prices.
- **Predict Price Direction:** Build a classification model (Logistic Regression) to determine price movement direction.
- **Feature Engineering:** Incorporate technical indicators like Lag values, MA_5, MA_20, and RSI.
- **EDA & Visualization:** Analyze trends and patterns using interactive visualizations.
- **Interactive Dashboard:** Enable real-time user input and stock visualization through a Streamlit-based interface.
- **Version Control & CI/CD:** Use GitHub and GitHub Actions for collaborative development and deployment automation.

---

## 🧠 Methodology
1. **Data Collection:**  
   - Historical stock data fetched using [`yfinance`](https://pypi.org/project/yfinance/) API.

2. **Data Preprocessing:**  
   - Handle missing values (dropna) from rolling calculations.
   - Outliers retained to preserve real market scenarios.

3. **Feature Engineering:**  
   - Lag_1, Lag_2 (previous day prices)  
   - MA_5, MA_20 (short and medium-term trends)  
   - RSI (14-day momentum indicator)  

4. **Model Development:**  
   - **Regression:** Random Forest Regressor  
   - **Classification:** Logistic Regression  

5. **Evaluation:**  
   - Regression: MAE, MAPE  
   - Classification: Accuracy, Precision, Recall, F1-Score  

6. **Visualization:**  
   - Actual vs Predicted Prices  
   - RSI chart with thresholds  
   - MA crossover signals  
   - Volatility and return trends  
   - Daily accuracy percentage bars  

7. **Deployment:**  
   - Streamlit Web App hosted online  

![workflow](https://github.com/user-attachments/assets/133c018b-15d0-4d11-8b9a-ae6b9c56ce97)


---

## 📌 Key Features

- Lag Values: Historical close prices (Lag_1, Lag_2)
- Moving Averages: 5-day and 20-day trend indicators
- RSI: Tracks price momentum and reversal signals
- Bollinger Bands: Measure volatility and deviation
- Interactive Plots: Plotly-based dynamic charting
- Daily Accuracy: Bar plots highlight prediction quality

---

## 📦 Data Source

- **API**: Yahoo Finance (`yfinance` library)
- **Data Type**: Time-series (OHLC + Volume)
- **Target Variables**:  
  - `Target_Price` (for regression)  
  - `Target_UpDown` (for classification)  

---

## ⚙️ Tools & Technologies

- **Language:** Python
- **IDE/Notebook:** VS Code, Jupyter, Axel DICE, Google Colab
- **Libraries:**  
  - `pandas`, `numpy` – Data processing  
  - `plotly`, `matplotlib`, `seaborn` – Visualization  
  - `scikit-learn` – Machine learning  
  - `streamlit` – Web dashboard  
  - `yfinance`, `appdirs` – Data and utility support

- **Deployment :**  
  - Streamlit (Web app hosting)  

---

## 🚀 Getting Started

1. **Clone the repository**  
```bash
git clone https://github.com/Vignesh-72/Stock-Price-Prediction-Model.git
cd Stock-Price-Prediction-Model
```

2. **Install dependencies**  
```bash
pip install -r requirements.txt
```

3. **Run the application**  
```bash
streamlit run streamlit_app.py
```

4. **Usage**  
- Enter a stock ticker (e.g., AAPL, GOOGL)  
- View predictions, trends, and trading recommendations

---

## 👥 Project Team

- **DHANESWARI S** – Model Building & Training  
- **CHAITANYA** – Front-End Design & Exploratory Data Analysis  
- **BHARGAVI** – Data Cleaning & Feature Engineering  
- **KADAMBINI** – Documentation & Reporting

---

> ⚠️ **Academic Integrity Notice**  
> This project was developed by **KADAMBINI and Team** for academic use at **FACULTY OF Engineering AND TECHNOLOGY EXCLUSIVELY FOR WOMENS SHARNBASAVA UNIIIVERSITY**. Unauthorized copying, modification, or submission of this project as your own academic or commercial work is strictly prohibited..

