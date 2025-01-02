# Bitcoin Data Analysis Project

## **Introduction**
This project provides an in-depth analysis of Bitcoin's historical price and volume data, exploring its trends, patterns, and volatility. By leveraging advanced data analytics techniques, this project uncovers actionable insights for traders and investors, focusing on key aspects like market cycles, price volatility, and predictive indicators.

---

## **Dataset**
- **Source**: [Bitcoin Historical Data on Kaggle](https://www.kaggle.com/mczielinski/bitcoin-historical-data)
- **Description**: Minute-level Bitcoin price and volume data from various exchanges, aggregated into daily data for simplicity and analysis.
- **Key Features**:
  - **Price Metrics**: Open, High, Low, Close prices.
  - **Volume**: Total Bitcoin traded daily.
  - **Additional Features**: Moving averages, momentum, Relative Strength Index (RSI), and significant price drops.

---

## **Analysis Overview**
1. **Data Preparation**:
   - Aggregated raw minute-level data into daily summaries.
   - Addressed missing values and placeholder timestamps.
   
2. **Feature Engineering**:
   - Developed technical indicators to identify trends and reversal points:
     - **Moving Averages**: 7-day, 30-day, 10-day, and 50-day.
     - **Momentum**: Speed of price changes over 10 days.
     - **RSI**: Overbought (RSI > 70) and oversold (RSI < 30) conditions.

3. **Exploratory Data Analysis**:
   - Examined daily price trends and monthly returns.
   - Analyzed Bitcoin’s price volatility using daily returns.
   - Visualized correlations and key trading patterns.

4. **Advanced Insights**:
   - Correlation between price, volume, and technical indicators.
   - Identification of significant price drops (>5%).
   - Insights into clustered extreme price changes during major events.

---

## **Key Insights**
1. **Volatility**:
   - Bitcoin exhibits significant daily price fluctuations, making it a high-risk, high-reward asset.
2. **Market Cycles**:
   - Alternating periods of rapid growth and corrections highlight speculative booms and busts.
3. **Predictive Indicators**:
   - Moving averages and RSI are effective tools for trend identification and potential buy/sell signals.
4. **Volume and Price Relationship**:
   - Moderate correlation between trading volume and price suggests additional external factors (e.g., sentiment, news) influence price movements.

---

## **Visualizations**
Key plots included in this project:
1. **Daily Closing Prices with Moving Averages**:
   - Highlights short- and long-term trends.
2. **RSI with Overbought/Oversold Levels**:
   - Identifies potential reversal points during extreme market conditions.
3. **Monthly Returns**:
   - Highlights speculative booms and market corrections.
4. **Distribution of Daily Returns**:
   - Reveals clustered extreme price changes during significant market events.

---

## **How to Run the Project**
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/Bitcoin-Data-Analysis.git
   cd Bitcoin-Data-Analysis

## **Next Steps**
1. **Strategy Backtesting**:
   Test the profitability of trading strategies based on RSI and moving average crossovers.
2. **Predictive Modeling**:
   Build models to forecast Bitcoin prices using engineered features (e.g., RSI, momentum).
3. **Event Mapping**:
   Investigate the impact of major events (e.g., Bitcoin halving, regulatory announcements) on price trends.

## **Acknowledgements**
Data sourced from Kaggle.
Inspired by Satoshi Nakamoto's revolutionary blockchain concept.
