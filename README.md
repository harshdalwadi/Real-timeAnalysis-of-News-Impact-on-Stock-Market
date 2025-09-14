# 📊 Real-Time Analysis of News Impact on Stock Market  

This repository contains data analysis, visualisation, and sentiment-based forecasting of the **stock market's response to news events**.  

---

## 📌 Project Overview  
This project explores how **news sentiment influences stock prices** by analysing **historical news headlines** and **stock market data**.  
We use **Machine Learning** for large-scale data processing and **Grafana** for interactive visualisation.  

Initially, we planned to use **Amazon Kinesis** for real-time analysis but later switched to **historical analysis** to derive deeper insights.  

---

## 📊 Dataset Description  
We leverage two key datasets for this analysis:  
- **News Headlines**: Collected from **Reddit’s WorldNews** channel.  
- **Stock Market Data**: Historical **Dow Jones Industrial Average (DJIA)** prices.  

These datasets provide valuable insights into how major news events impact stock movements.

### 📂 Data Files  
- `news_headlines.csv` - Contains historical news headlines.  
- `djia_stock_prices.csv` - Stock market prices over time.  

---

## 🔍 Data Processing & Analysis  

### 1️⃣ Data Cleaning & Preprocessing  
- Removed irrelevant news articles unrelated to financial markets.  
- Standardised timestamps for accurate **time-series analysis**.  
- **Tokenised and preprocessed** news headlines for sentiment analysis.  

### 2️⃣ Sentiment Analysis & Feature Engineering  
- Applied **Natural Language Processing (NLP)** techniques.  
- Classified news as **positive, negative, or neutral**.  
- Extracted sentiment scores to quantify market sentiment trends.  

### 3️⃣ Exploratory Data Analysis (EDA)  
- **Stock Price Trends**: Identified major fluctuations.  
- **Impact of Breaking News**: Measured market reaction to key events.  
- **Correlation Analysis**: Compared sentiment scores with DJIA price changes.  

### 4️⃣ Visualization & Insights  
- **Bubble Charts**: Displaying top words in news sentiment.  
- **Stock Market Trend Graphs**: Overlaid with major news events.  
- **Interactive Grafana Dashboards**: Real-time sentiment tracking.  

![Stock Market Trends](https://github.com/harshdalwadi/Real-time-Analysis-of-News-Impact-on-Stock-Market-using-Apache-Beam/blob/main/newplot.png)  

---

## 📈 Key Findings  
✔ **Negative sentiment in the news often correlates with stock declines.**  
✔ **Major financial events significantly impact stock prices.**  
✔ **Sentiment-driven stock forecasting has strong predictive potential.**  
✔ **Real-time tracking can enhance trading strategies for investors.**  

---

## 🚀 Recommendations  
🔹 **Real-time implementation**: Leverage **Kafka** or **Amazon Kinesis** for live updates.  
🔹 **Expanded dataset**: Include **S&P 500, NASDAQ** & crypto markets.  
🔹 **Machine Learning Integration**: Use **LSTM models** for improved prediction accuracy.  
🔹 **Event-driven trading strategies**: Develop **algorithmic trading models**.  

---

## 🛠️ Technology Stack  
- **Programming Language**: Python 3.x  
- **Data Processing**: Apache Beam  
- **Visualization**: Grafana, Plotly  
- **NLP & Sentiment Analysis**: NLTK, VADER  
- **Jupyter Notebooks** for development  

## 👥 Contributors
- **Harsh Dalwadi** – Data Analysis & Machine Learning
- **Krutarth Majmundar** – Visualization & Reporting

## 📜 License
This project is licensed under the **MIT License**. Contributions are welcome! 🚀

