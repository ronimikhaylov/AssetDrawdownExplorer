# Financial Data Analysis and Visualization



https://github.com/ronimikhaylov/isharesp3/assets/105238029/88f5f51f-311e-40c4-9fbd-2b64acd58fcc



This repository contains code for analyzing and visualizing financial data using Python. The code leverages various libraries such as SciPy, pandas, NumPy, yfinance, ipywidgets, and plotly.

## Code Overview

The code is organized into different sections, each serving a specific purpose. Here's a brief overview of each section:

1. **Dependencies**: This section imports the necessary libraries required for the analysis.

2. **Fetching Data**: The code fetches historical stock price data for a list of funds using the Yahoo Finance API. The data is stored in a dictionary where each fund's data is associated with its ticker symbol.

3. **Compute Drawdowns**: This section defines a function to calculate drawdowns, which measure the decline from a historical peak in an investment.

4. **Plot Rolling Correlation**: The code defines a function to plot the rolling correlation between two funds over a specified window. It uses the closing price data for the selected funds and calculates the rolling correlation using a sliding window.

5. **Plot CDF of Correlations**: The code defines a function to plot the Cumulative Distribution Function (CDF) of rolling correlations for all combinations of funds. It computes the rolling correlation between each pair of funds and then generates the CDF plot.

6. **Fund Drawdowns**: This section defines a function to analyze and display the drawdowns of the funds. It calculates the drawdowns for each fund, filters them based on a threshold, and presents the results in a table format.

## License

This code is released under the [MIT License]([LICENSE](https://opensource.org/license/mit/)), which is a popular open-source license granting permissions to use, modify, and distribute the code.

Contributions and suggestions are also welcome!
