## 📊INFY-Stock-Analysis-Prediction

## 📌 Overview

This project analyses historical stock data of Infosys (INFY.NS) to understand price trends, volatility, and feature relationships.
A machine learning model is developed to predict the next-day stock price direction (UP/DOWN) using basic technical indicators, including moving averages, returns, and volatility.


## 🎯 Objective

* Analyse stock price trends and behaviour
* Understand relationships between key financial features
* Predict next-day stock movement using a classification model

---

## 🛠 Tools & Technologies

* Python (Pandas, NumPy)
* Data Visualisation (Matplotlib, Seaborn)
* Machine Learning (Scikit-learn)
* Data Source: Yahoo Finance (yfinance)

---

## 📊 Exploratory Data Analysis

* The stock shows a long-term upward trend with periodic fluctuations
* Daily returns are centred around zero with occasional spikes
* Volatility increases during certain periods, indicating market instability

---

## 🔗 Correlation Analysis

* Moving averages (MA10, MA50) are strongly correlated with price but weakly related to direction
* Returns and volatility show very low correlation with the target variable
* No feature shows strong predictive power for next-day movement

---

## 🤖 Model

* Model: Logistic Regression
* Features: MA10, MA50, Return, Volatility
* Target: Next-day price direction (UP = 1, DOWN = 0)
* Accuracy: ~50–55%

---

## 🔍 Key Insights

* Moving averages (MA10, MA50) are highly correlated with price levels but offer little value in predicting future direction, as they are lagging indicators.
* Returns and volatility show near-zero correlation with the target variable, confirming weak relationships with next-day movement.
* The absence of strong feature-target relationships suggests that stock direction is not linearly predictable using simple technical indicators.
* The model’s low performance reinforces that stock movements are driven by complex, external factors such as news, sentiment, and macroeconomic conditions, which    are not captured in this dataset.
* Improving prediction accuracy requires richer features (technical indicators, lag variables, or external data) and more advanced modelling approaches.

  ---

  ## ⚠️ Conclusion

This project analyzed Infosys (INFY.NS) stock data and attempted to predict next-day price direction using basic technical indicators.
The model achieved accuracy close to random guessing (~50–55%), indicating that these features fail to capture meaningful predictive patterns.
This highlights the limitation of relying solely on historical price-based indicators for short-term stock direction prediction.
