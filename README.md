# Bitcoin-Data-Analysis
Introduction

This project analyzes historical Bitcoin data to uncover trends, patterns, and actionable insights. The analysis includes data aggregation, feature engineering, exploratory data analysis (EDA), and advanced statistical techniques.

Dataset

The dataset contains minute-level Bitcoin price and volume data sourced from Kaggle. Key features include:

Open, High, Low, Close Prices: Daily trading prices.

Volume: Total Bitcoin traded daily.

Data Quality Issues

Missing values in key columns.

Placeholder timestamps (e.g., 1970-01-01) with no valid data.

NaN values in rolling features due to insufficient data for early rows.

Project Structure

Bitcoin-Data-Analysis/
├── data/
│   └── btcusd_1-min_data.csv  # Raw dataset
├── scripts/
│   └── analysis_script.py     # Python script for analysis
├── visuals/
│   └── trend_analysis.png     # Generated plots
│   └── rsi_plot.png
├── report/
│   └── Bitcoin_Analysis_Report.md  # Full report
└── README.md                  # Project documentation

Analysis Overview

Feature Engineering

Moving Averages:

7-day and 30-day moving averages to capture short- and long-term trends.

Momentum:

Speed of price changes over a 10-day window.

RSI (Relative Strength Index):

Overbought and oversold conditions.

Exploratory Data Analysis (EDA)

Summary Statistics:

Average Closing Price: $241.87

Price Range: $4.38 to $1,143.09

Average Daily Trading Volume: 864 BTC

Trend Analysis:

Identified price surges and stabilization over time.

Volatility Analysis:

Long tails in daily returns emphasize Bitcoin's high-risk, high-reward nature.

Volume vs. Price:

Moderate correlation (0.405), with external factors driving price changes.

Advanced Analysis

Correlation Matrix:

Strong positive correlation between momentum and RSI.

Significant Price Drops:

Identified >5% drops and linked them to market corrections or external events.

RSI Visualization:

Highlighted overbought (RSI > 70) and oversold (RSI < 30) conditions.

Visualizations

Key plots include:

Trend Analysis: Daily closing prices with 7-day and 30-day moving averages.

RSI Levels: Overbought and oversold thresholds.

Volume vs. Price: Scatter plot showing moderate correlation.

Monthly Returns: Bar chart of average monthly returns.

How to Use

Clone the Repository:

git clone https://github.com/your-username/Bitcoin-Data-Analysis.git

Install Dependencies:

pip install -r requirements.txt

Run the Script:

python scripts/analysis_script.py

View Outputs:

Visualizations will be saved in the visuals/ directory.

The full analysis report is available in report/Bitcoin_Analysis_Report.md.

Key Insights

Volatility: Bitcoin exhibits extreme price fluctuations, posing opportunities and risks.

Market Cycles: Boom-and-bust cycles driven by adoption, speculation, and external events.

Indicators: Moving averages and RSI provide actionable insights for trading strategies.

Next Steps

Backtesting: Evaluate the profitability of RSI- and momentum-based strategies.

Predictive Modeling: Use features like RSI and momentum for forecasting.

Event Analysis: Investigate the impact of regulatory announcements on Bitcoin prices.

Contributors

Your Name: Data analysis, report generation, and visualizations.

License

This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgments

Dataset source: Kaggle.

Inspiration: Bitcoin's unique position as a speculative and transformative asset.

