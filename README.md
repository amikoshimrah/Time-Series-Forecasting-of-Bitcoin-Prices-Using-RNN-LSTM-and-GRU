# 💹 Time Series Forecasting of Bitcoin Prices Using RNN, LSTM & GRU

## 📘 Project Summary
This project demonstrates **Time Series Forecasting** for **Bitcoin (BTC-USD)** using advanced **Recurrent Neural Network (RNN)** architectures — **SimpleRNN**, **LSTM**, and **GRU**.

The notebook focuses on analyzing and predicting Bitcoin price movements through deep learning models capable of capturing temporal dependencies and long-term patterns in financial time series data.

---

## 📊 Objectives
- Fetch and preprocess historical Bitcoin price data from **Kagglehub**
- Perform **Exploratory Data Analysis (EDA)** with moving averages and volatility trends
- Transform time series data for supervised learning
- Train and tune **RNN**, **LSTM**, and **GRU** models
- Compare model performance using metrics like **RMSE** and **MAE**
- Visualize predicted vs. actual Bitcoin prices

---

## 🧩 Workflow Summary

### 1. **Data Collection**
- Source:  [Bitcoin Historical Price Dataset (Kaggle)](https://www.kaggle.com/datasets/mczielinski/bitcoin-historical-data)
- Ticker: `BTC-USD`
- Data includes **Open, High, Low, Close, Volume**, and **Date** columns.

### 2. **Data Preprocessing**
- Handling missing values and formatting timestamps  
- Normalization using `MinMaxScaler`  
- Creating supervised sequences (look-back windows)

### 3. **Exploratory Data Analysis**
- Visualized Bitcoin price trends  
- Computed moving averages for short-term and long-term trends  
- Analyzed volatility and rolling standard deviation  

### 4. **Model Building**
Built and trained three recurrent architectures for performance comparison:
- **SimpleRNN** – Baseline sequential model  
- **LSTM** – Long Short-Term Memory model to capture long-term dependencies  
- **GRU** – Gated Recurrent Unit model for efficient training  

### 5. **Evaluation Metrics**
Models were evaluated using:
- **Root Mean Square Error (RMSE)**  
- **Mean Absolute Error (MAE)**  

### 6. **Visualization**
Plotted actual vs. predicted Bitcoin prices to analyze model accuracy and lag behavior.  
Compared model performances visually and statistically.

---

## ⚙️ Tools & Libraries Used
- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib**
- **Seaborn**
- **TensorFlow / Keras**
- **Scikit-learn**
- **Statsmodels**
- **yFinance**

---

## 🧠 Key Learnings
- Mastered time series transformation for supervised learning  
- Understood differences in RNN, LSTM, and GRU architectures  
- Learned how to fine-tune models for better temporal forecasting  
- Gained insight into real-world cryptocurrency trend prediction  

---

## 🧮 Results
- All models successfully captured Bitcoin price trends.  
- **LSTM** and **GRU** demonstrated better generalization and lower RMSE than SimpleRNN.  
- Visualizations showed smooth alignment between predicted and actual prices over time.

---

## 👨‍🏫 Mentors
- **Chirag Jhumkhawala**  
- **KARKAVELRAJA J**  
- **Pranav**

---

## 🔗 Resources
- 📂 Data Source: [Yahoo Finance](https://finance.yahoo.com/quote/BTC-USD)  
- 💻 Code Repository: [Add your GitHub project link here]

---

## 🏷️ Tags
`Deep Learning` `Time Series` `RNN` `LSTM` `GRU` `Forecasting` `Bitcoin` `TensorFlow` `Finance`

---

⭐ *If you found this project helpful, please consider giving it a star on GitHub!*
