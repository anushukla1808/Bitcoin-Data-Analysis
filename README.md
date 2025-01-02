# Bitcoin Data Analysis Project

## **Introduction**
This project explores historical Bitcoin data to uncover trends, patterns, and actionable insights. The analysis includes data aggregation, feature engineering, exploratory data analysis (EDA), and advanced statistical techniques. The project provides insights into Bitcoin’s price volatility, market cycles, and predictive indicators for traders and investors.

---

## **Dataset**
- **Source**: [Original Dataset](https://www.kaggle.com/mczielinski/bitcoin-historical-data)
- **Description**: Minute-level Bitcoin price and volume data from various exchanges, aggregated to daily frequency.
- **Features**:
  - **Open, High, Low, Close Prices**: Daily trading prices.
  - **Volume**: Total Bitcoin traded daily.

---

## **Analysis Steps**
1. **Data Cleaning and Aggregation**:
   - Aggregated minute-level data to daily frequency.
   - Addressed missing values and placeholder timestamps.
   
2. **Feature Engineering**:
   - Created additional features:
     - **Moving Averages**: 7-day, 10-day, 30-day, and 50-day.
     - **Momentum**: Measures price speed over a 10-day window.
     - **RSI (Relative Strength Index)**: Identifies overbought and oversold conditions.

3. **Exploratory Data Analysis (EDA)**:
   - Trend analysis of daily closing prices.
   - Volatility analysis using daily returns distribution.
   - Monthly returns analysis to understand market cycles.

4. **Advanced Analysis**:
   - Correlation analysis between key features.
   - Identification of significant price drops (>5%).
   - Visualization of RSI alongside overbought and oversold thresholds.

---

## **Key Insights**
1. **Volatility**:
   - Bitcoin exhibits extreme price fluctuations, emphasizing its high-risk, high-reward nature.
2. **Market Cycles**:
   - Alternating periods of rapid growth and corrections highlight Bitcoin’s boom-and-bust cycles.
3. **Predictive Indicators**:
   - Moving averages and RSI effectively capture trends and reversal points.
4. **Volume and Price Relationship**:
   - Moderate correlation between volume and price suggests other factors (e.g., sentiment, events) play a significant role.

---

## **Visualizations**
The project includes the following key visualizations:
1. **Daily Closing Prices with Moving Averages**:
   - Identifies trends and crossovers for potential buy/sell signals.
2. **RSI with Overbought/Oversold Levels**:
   - Highlights potential reversal points during extreme price movements.
3. **Monthly Returns**:
   - Displays speculative booms and market corrections over time.
4. **Distribution of Daily Returns**:
   - Reveals clustered extreme price changes during major events.

---

## **How to Use**
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/Bitcoin-Data-Analysis.git
   cd Bitcoin-Data-Analysis
