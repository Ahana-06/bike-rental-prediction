# 🚲 Bike Rental Prediction using Time Series Machine Learning
 This project builds a time series forecasting model to predict bike rental demand using trend, seasonality, and machine learning techniques.


## 📁 Project Structure

bike-rental-prediction/
│
├── images/
│   ├── decomposition.png
│   ├── rolling.png
│   ├── final.png
│
├── main.py
├── requirements.txt
├── README.md


## 📸 Project Preview
![Final](images/final.png)


## 📌 Problem Statement
Accurately predicting bike rental demand helps optimize resource allocation and improves operational efficiency.
This project simulates real-world rental patterns and applies machine learning to forecast demand.


## 📊 Dataset
This project uses a synthetic time series dataset generated with:

 📈 Trend (increasing demand over time)
 🔁 Seasonality (weekly patterns)
 🎲 Noise (random variation)


## ⚙️ Project Workflow
1. Data Generation
Created time-based dataset with realistic patterns

2.Exploratory Data Analysis (EDA)
 Time series decomposition (Trend, Seasonal, Residual)
 Rolling mean visualization

3.Feature Engineering
Lag features (`lag_1`, `lag_7`)
Rolling mean features

4.Model Training
Random Forest Regressor

5.Evaluation
Compared with baseline (naive model)
Metrics: MAE, RMSE


## 🔄 Machine Learning Pipeline
Data → Feature Engineering → Train/Test Split → Model → Evaluation


## 📈 Results
 🔹 Time Series Decomposition
![Decomposition](images/decomposition.png)

 🔹 Trend & Rolling Mean
![Rolling](images/rolling.png)

 🔹 Final Prediction vs Actual
![Final](images/final.png)


## 📊 Model Performance
--- Model Comparison ---
[Baseline (Naive)] MAE: 2.34 | RMSE: 3.12
[Random Forest] MAE: 1.85 | RMSE: 2.60

## 🛠️ Tech Stack
* Python
* Pandas, NumPy
* Matplotlib, Seaborn
* Scikit-learn
* Statsmodels


## 🚀 How to Run the Project

```bash
pip install -r requirements.txt
python main.py
```


## 💡 Key Insights

* Time series data contains trend and seasonality patterns
* Feature engineering significantly improves model performance
* Random Forest outperforms naive baseline predictions


## 📌 Future Improvements

 Use real-world bike rental dataset
 Try advanced models (XGBoost, LSTM)
 Hyperparameter tuning
 Deploy as a web app


