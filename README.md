# Yahoo_Finance_Currency_Analysis

This repository contains a comprehensive project that analyzes the EUR/INR currency pair using data sourced from Yahoo Finance. The analysis spans from January 1, 2023, to September 30, 2024, and focuses on deriving actionable insights using technical indicators. The project is designed to assist in making informed BUY, SELL, or NEUTRAL decisions based on historical currency data.

## Objective
The main goals of this project are:
1. Data Acquisition: Scrape EUR/INR currency data from Yahoo Finance for the specified period.
2. Technical Analysis: Calculate and analyze the following indicators:
   - Moving Average (1-day and 1-week)
   - Bollinger Bands
   - Commodity Channel Index (CCI)
3. Decision Making: Use the computed indicators to provide recommendations on whether to BUY, SELL, or remain NEUTRAL for the EUR/INR pair.

---

## Technical Indicators Used
### 1. Moving Average
- Calculates the average price of the currency pair over a specific period.
- Helps smooth out price data to identify trends more clearly.

### 2. Bollinger Bands
- Consist of a moving average and two standard deviations plotted above and below the average.
- Used to identify overbought or oversold conditions in the market.

### 3. Commodity Channel Index (CCI)
- Measures the deviation of the currency price from its average price over a specified period.
- Indicates whether the market is overbought (> 100) or oversold (< -100).

---

## Features
- Data Preprocessing: Cleaning and formatting raw data for analysis.
- Indicator Calculations: Implementing the mathematical formulas for each indicator.
- Visualization: Plotting charts to visually interpret trends, Bollinger Bands, and trading signals.
- Signal Identification: Highlighting BUY and SELL signals based on the indicator thresholds.

---

## Tools & Libraries
- Python: Core programming language used for analysis.
- Pandas: Data manipulation and preprocessing.
- NumPy: Numerical computations.
- Matplotlib & Seaborn: Data visualization.

---

## How It Works
1. The EUR/INR historical data is loaded and preprocessed to ensure accuracy.
2. Moving Average, Bollinger Bands, and CCI are calculated for the specified timeframe.
3. Visualizations are created to highlight trends and potential trading signals.
4. Recommendations are generated based on the computed indicators for the one-day and one-week periods.

---

## Key Outputs
- Moving Averages: Highlighting short-term and weekly trends.
- Bollinger Bands: Identifying overbought and oversold conditions.
- CCI Values: Pinpointing market momentum and deviations.
- Trading Signals: Final BUY, SELL, or NEUTRAL recommendations based on combined indicators.

---

## Usage
Clone this repository and follow the instructions in the provided notebook or script files to replicate the analysis. Ensure the required libraries are installed before running the code.

---

## License
This project is open-source and available under the MIT License.

---






