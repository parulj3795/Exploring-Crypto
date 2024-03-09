# Cryptocurrency Analysis Project

This project demonstrates the use of various Python libraries to fetch, analyse, and backtest cryptocurrency trading strategies. It leverages CCXT for market data access, TA-Lib for technical analysis, and Backtrader for strategy backtesting.

## Overview

The project consists of three Jupyter Notebooks that cover different aspects of cryptocurrency trading analysis:

1. **Data Fetching**: Uses CCXT to fetch historical cryptocurrency data.
2. **Technical Analysis**: Applies TA-Lib to compute technical indicators such as SMA and EMA.
3. **Strategy Backtesting**: Implements and backtests a simple trading strategy using Backtrader.

## Getting Started

### Prerequisites

Ensure you have Python 3.x installed on your system. You will also need JupyterLab or Jupyter Notebook to run the notebooks.

### Installation

Clone this repository to your local machine:

```bash
git clone https://github.com/parulj3795/Exploring-Crypto.git
cd Exploring-Crypto
```

Install the required Python packages:
```bash
pip install -r requirements.txt
```

### Notebooks

0. [Bitcoin-EDA-Basic.ipynb](/Bitcoin-EDA-Basic.ipynb) and [Bitcoin-EDA-Advance.ipynb](/Bitcoin-EDA-Advance.ipynb) showcase exploratory data analysis of Bitcoin data, retrieved from Kaggle.   
1. [GetData-using-CCXT.ipynb](/GetData-using-CCXT.ipynb): Demonstrates how to use CCXT to fetch historical cryptocurrency data.
2. [AnalyseData-using-TAlib.ipynb](/AnalyseData-using-TAlib.ipynb): Shows how to apply technical indicators using TA-Lib.
3. [BackTest-using-Backtrader.ipynb](/BackTest-using-Backtrader.ipynb): Implements a simple moving average crossover strategy and backtests it using Backtrader.


### Contributing

Contributions to this project are welcome! Please fork the repository, make your changes, and submit a pull request.

### License

This project is licensed under the MIT License.