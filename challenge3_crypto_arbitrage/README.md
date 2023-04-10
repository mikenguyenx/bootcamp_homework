# Bitcoin Arbitrage Analysis

This Jupyter notebook contains code related to an analysis that determines Bitcoin arbitrage profit opportunities through price dislocations on markets across the globe.  With this analysis, arbitrage profits can be calculated leveraging historical trade data for Bitcoin on two exchanges: Bitstamp and Coinbase. The analysis performed uses the Pandas framework for data manipulation & analysis and Matplotlib for data visualizations to plot out profitability metrics.

## Technologies

Programming Language: Python

Interactive Development Environment: JupyterLab


Libraries: 
- Pandas - A Python library that is used for data manipulation, analysis, and visualization. 
- Pathlib - A Python module that provides an object-oriented interace to working with files & directories.
- Matplotlib - A Python library used for data visualization. 

Operating System(s):  Any operating system that supports Python, including Windows & macOS.

## Installation Guide

To run the application:

1. Clone the repository: `git clone https://github.com/mikenguyenx/bootcamp_homework/tree/main/challenge3_crypto_arbitrage`
2. Launch Jupyter Lab: `jupyter lab`
3. Open `crypto_arbitrage.ipynb` in Jupyter Lab to view and run the data analysis code.
4. The script will load data from two different exchanges (Bitstamp & Coinbase) and compare the prices of the cryptocurrency on each exchange, identifying opportunities for arbitrage.


## Usage

To use the crypto arbitrage analysis script:

1. Open `crypto_arbitrage.ipynb` in Jupyter Lab.
2. Run the code cells by clicking on the run button or by pressing the "Shift + Enter" key combination to load and preprocess the data, and generate visualizations
3. The script uses Pandas to collect CSV data into the Jupyter notebook file for analysis using summary statistics and Matplotlib for visualizations.

Below are screenshots of examples of results from the analysis:

Data Analysis - Summary Statistics

![summary_statistics](challenge3_crypto_arbitrage/summary_statistics.png)

Data Analysis - Overlay Plot Visualization

![overlay_plot](https://github.com/mikenguyenx/bootcamp_homework/blob/main/challenge3_crypto_arbitrage/overlay_plot_visualization.png)

Data Analysis - Focus on Specific Date

![day_arbitrage](https://github.com/mikenguyenx/bootcamp_homework/blob/main/challenge3_crypto_arbitrage/day_arbitrage_analysis.png)

Arbitrage Profits - Summary Statistics & Visualization

![profit_per_trade](https://github.com/mikenguyenx/bootcamp_homework/blob/main/challenge3_crypto_arbitrage/profit_per_trade_visualization.png)

Cumulative Profit - Trend Analysis

![cumsum](https://github.com/mikenguyenx/bootcamp_homework/blob/main/challenge3_crypto_arbitrage/cumsum.png)


## Contributors

Mike Nguyen

Email: nguyen.mikeq@gmail.com

LinkedIn: https://www.linkedin.com/in/mike-nguyen-6899554/

## License

MIT