# NASDAQ Historical Daily Prices Dataset

This repository refers to the work of Oleh Onyshchak from Kaggle (https://www.kaggle.com/datasets/jacksoncrow/stock-market-dataset), which contains historical daily prices for all tickers currently trading on the NASDAQ. The data has been sourced from Yahoo Finance using the `yfinance` Python package. An up-to-date list of NASDAQ tickers is available at [nasdaqtrader.com](https://www.nasdaqtrader.com).

## 📅 Dataset Summary
- **Coverage:** Historical prices up to today**January 23, 2025**.
- **File Format:** CSV files for each ticker.
- **Data Update:** To retrieve more recent data, fork this repository and run the included data collection script.

## 📂 Data Structure
Each ticker's data is stored in a CSV file with the following fields:

| **Field**     | **Description**                                                                     |
|---------------|-------------------------------------------------------------------------------------|
| `Date`        | Trading date                                                                       |
| `Open`        | Opening price of the trading day                                                   |
| `High`        | The highest price reached during the day                                           |
| `Low`         | The lowest price reached during the day                                            |
| `Close`       | Closing price, adjusted for stock splits                                           |
| `Adj Close`   | Adjusted closing price, accounting for both dividends and splits                   |
| `Volume`      | Total number of shares traded during the day                                       |

## 📁 Folder Organization
- **ETFs**: Contains CSV files for exchange-traded funds.
- **Stocks**: Contains CSV files for individual stocks.
- **etfs**: Contains CSV files for exchange-traded funds without format changes (Oleh Onyshchak's version).
- **Stocks**: Contains CSV files for individual stocks without format changes (Oleh Onyshchak's version).
- Each file is named after its corresponding ticker symbol (e.g., `AAPL.csv` for Apple Inc.).
- Metadata for all tickers, such as their full names, is available in the `symbols_valid_meta.csv` file.

## 🚀 How to Use
1. Browse the CSV files to access historical price data for specific tickers.
2. Refer to the `symbols_valid_meta.csv` file for ticker metadata and identification.
3. To get updated data:
   - Fork this repository.
   - Execute the data collection script available in the repository.

## 💡 Applications
This dataset is suitable for:
- Financial analysis
- Backtesting trading strategies
- Stock market trend exploration
- Machine learning models for market prediction

## 📜 License
This project is licensed under the MIT License. Feel free to use, modify, and distribute this dataset as needed.

---

### ⭐ Contributions
Contributions are welcome! Feel free to submit a pull request or raise issues for any suggestions or improvements.

---

### 📧 Contact
For questions or support, feel free to contact the repository maintainer via GitHub or leave a comment in the Issues section.
