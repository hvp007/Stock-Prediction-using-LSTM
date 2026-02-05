# 📈 Stock Market Analysis + Prediction using LSTM

## 📌 Project Overview
This project is a comprehensive data analysis and machine learning experiment focused on the stock market, specifically targeting major technology stocks: **Apple (AAPL), Amazon (AMZN), Google (GOOG), and Microsoft (MSFT)**.

The goal is to explore historical stock data, visualize trends, analyze risk, and ultimately build a **Long Short-Term Memory (LSTM)** neural network to predict future stock prices for Apple Inc.

## 🚀 Key Objectives
The notebook addresses the following analytical questions:
1.  **Price Analysis:** How has the stock price changed over time?
2.  **Daily Returns:** What is the average daily return of these stocks?
3.  **Trend Analysis:** What are the moving averages of the various stocks?
4.  **Correlation:** How are different tech stocks correlated with each other?
5.  **Risk Assessment:** How much value is at risk by investing in a particular stock?
6.  **Prediction:** Can we accurately predict the future closing price of Apple (AAPL) using an LSTM model?

## 🛠️ Technologies & Libraries
* **Python 3**
* **Data Collection:** `yfinance`, `pandas_datareader`
* **Data Processing:** `pandas`, `numpy`
* **Visualization:** `matplotlib`, `seaborn`
* **Deep Learning:** `keras` / `tensorflow` (for LSTM)

## 📂 Dataset
Real-time and historical stock data is scraped directly from **Yahoo Finance** using the `yfinance` API. The analysis covers a 1-year historical period from the date of execution.

## 📊 Key Insights & Visualizations
* **Moving Averages:** Used to smooth out price data and identify trends over specific time windows (e.g., 10, 20, 50 days).
* **Correlation Matrix:** visualized the relationship between daily returns of different tech giants.
* **Risk Analysis:** quantified the risk vs. expected return for each stock.
* **LSTM Prediction:** The final model predicts the "Close Price" of Apple stock.
    * *Model Performance:* RMSE (Root Mean Squared Error): **8.23** (approx.)

## ⚙️ Installation & Usage

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/hvp007/stock-market-analysis-lstm.git](https://github.com/hvp007/stock-market-analysis-lstm.git)
    cd stock-market-analysis-lstm
    ```

2.  **Install dependencies:**
    ```bash
    pip install pandas numpy matplotlib seaborn yfinance pandas_datareader keras tensorflow
    ```

3.  **Run the Notebook:**
    Launch Jupyter Notebook or upload the file to Google Colab.
    ```bash
    jupyter notebook "Stock Market Analysis + Prediction using LSTM.ipynb"
    ```

## 🤝 Contributing
Feel free to fork this repository and experiment with different stock symbols, timeframes, or LSTM architectures. Pull requests are welcome!

## 📜 License
[MIT](https://choosealicense.com/licenses/mit/)
