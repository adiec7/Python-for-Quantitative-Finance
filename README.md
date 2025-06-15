# Python for Quantitative Finance: Charting & Analysis Scripts

A collection of Python scripts designed to fetch financial data from MetaTrader 5, perform technical analysis, and generate high-quality charts for quantitative research.

## Overview

These scripts demonstrate how to programmatically apply common trading concepts, from detecting candlestick patterns to plotting advanced, adaptive indicators. They are intended for educational purposes to showcase the power of Python in quantitative finance.

## Features

This collection includes scripts for:
- **Pattern Detection:** Find single-candle (Doji) and multi-candle (Three White Soldiers) patterns in live market data.
- **Indicator Plotting:** Visualize classic indicators like MACD and compare different types of Moving Averages (SMA vs. EMA).
- **Algorithmic Trendlines:** Automatically identify and draw the most significant support and resistance trendlines.
- **Advanced Indicators:** Implement and plot an ATR-Adaptive Moving Average that adjusts its sensitivity based on market volatility.
- **Custom Chart Styling:** Includes a custom `mplfinance` style to create beautiful, "TradingView-like" dark-theme charts.

## Prerequisites

Before you begin, ensure you have the following installed and running:

1.  **Python 3.8+**
2.  **The MetaTrader 5 Desktop Terminal:** These scripts connect directly to the desktop application. It must be installed and running.
3.  **A MetaTrader 5 Broker Account:** You must be logged into a demo or live trading account within the MT5 terminal.

**IMPORTANT:** The `MetaTrader5` Python library is officially supported on **Windows only**. These scripts will not work on macOS or Linux.

## Setup & Installation

1.  **Download the Files:** Download all the `.ipynb` scripts, `requirements.txt`, and this `README.md` file into a new folder on your computer.

2.  **Open Your Terminal:** Navigate to the folder where you saved the files using the `cd` command.
    ```bash
    cd path/to/your/project-folder
    ```

3.  **Install Required Libraries:** Run the following command to install all necessary Python packages from the `requirements.txt` file.
    ```bash
    pip install -r requirements.txt
    ```

## How to Run a Script

Each `.ipynb` file is a standalone example that you can run directly.

1.  **Open a Script:** Open any script (e.g., `adaptive_MA.ipynb`) in a code editor.
2.  **Adjust Parameters (Optional):** At the bottom of each script, inside the `if __name__ == "__main__":` block, you can change the parameters like `SYMBOL`, `TIME_FRAME`, and `NUM_BARS` to analyze different assets.
3.  **Run from Terminal:** Execute the script from your terminal using the following command:
    ```bash
    click play icon in vscode 
    ```
4.  **Check the Output:** The script will log its progress in the terminal and save the final chart image (e.g., `BTCUSD_AMA_chart.png`) in the same folder.

## Disclaimer

The content and code provided are for educational and informational purposes only. They do not constitute financial advice or a recommendation to buy or sell any security. Trading and investing involve substantial risk, and you should conduct your own research before making any financial decisions.