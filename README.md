# StockEngine

A powerful stock analysis platform that empowers investors with advanced data visualization, comprehensive technical analysis, and interactive comparison tools.

![Dashboard](attached_assets/dashboard.avif)

## Features

### 🎯 Single Stock Analysis
- Real-time stock price data visualization
- Interactive candlestick charts with volume data
- Advanced technical indicators:
  - Bollinger Bands
  - MACD (Moving Average Convergence Divergence)
  - Stochastic Oscillator
  - ATR (Average True Range)
  - OBV (On-Balance Volume)

### 📊 Stock Comparison (Not Currently Working)
- Compare multiple stocks simultaneously
- Normalized price performance visualization
- Volume comparison analysis
- Key metrics comparison table

### 📈 Technical Analysis
- Moving averages (SMA20, SMA50)
- Momentum indicators
- Volatility analysis
- Trend identification tools

### 📉 Mathematical Analysis
- Statistical metrics calculation
- Volatility analysis
- Performance metrics
- Risk assessment tools

## Setup

1. Clone the repo
2. Install the required dependencies:

```bash
pip3 install streamlit yfinance pandas numpy plotly ta
```

3. Run the application:
```bash
streamlit run main.py

# or if that does not work

python3 -m streamlit run main.py
```

## Usage

1. **Single Stock Analysis**:
   - Enter a stock symbol (e.g., "AAPL" for Apple)
   - Select the time period and interval
   - Explore various technical indicators and charts

2. **Stock Comparison**: # Not Working
   - Enter multiple stock symbols separated by commas (e.g., "AAPL, MSFT, GOOGL")
   - View comparative performance charts
   - Analyze relative metrics

## Dependencies

- streamlit
- yfinance
- pandas
- numpy
- plotly
- ta
