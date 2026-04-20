## MSc-Data-Science-Project-
Time Series Forecasting and Prediction of Bitcoin Prices Using LSTM, GRU, and Transformer-Based Deep Learning Models


## 📌 Overview
This project predicts Bitcoin (BTC-USD) prices using deep learning models on historical data from **2014–2025**.  
Models used: **LSTM, GRU, Tuned LSTM, Transformer**.

---

## 📊 Dataset
- Source: Yahoo Finance (`yfinance`)
- Records: 4123
- Features: Date, Open, High, Low, Close, Volume

---

## ⚙️ Workflow
1. Data Collection & Cleaning  
2. Exploratory Data Analysis (EDA)  
3. Feature Engineering  
4. Model Training  
5. Forecasting (3 months & 1 year)

---

## 🤖 Models

- **LSTM** → Stable & reliable predictions  
- **GRU** → Best performance (lowest error)  
- **Tuned LSTM** → Overfitting (poor results)  
- **Transformer** → Underperformed on this dataset  

---

## 🔮 Forecast
- LSTM predicts **steady upward trend**
- GRU shows **more volatility**
- Recursive forecasting used for future predictions

---

## 🚀 Run the Project on Google Colab

### Step 1: Open Colab
Go to 👉 https://colab.research.google.com/

### Step 2: Install Required Libraries
python
!pip install yfinance pandas numpy matplotlib seaborn scikit-learn tensorflow

### Step 3: Upload Notebook / Code
- Upload `.ipynb` file  

### Step 4: Run All Cells
- Click **Runtime → Run All**  
- Wait for the models to train  

### Step 5: Output
After execution Outputs are:
- Model training logs  
- Evaluation metrics (RMSE, MAE, R², MAPE)  
- Forecast plots (3 months & 1 year)  
