

# Crypto Arbitrage Analysis

This README presents an analysis of historical data on Bitcoin prices for the period from January 1 through April 1st, 2018. The purpose of this analysis is to determine if there were any arbitrage opportunities for Bitcoin on two exchanges, Bitstamp and Coinbase, and quantify how large these arbitrage profits could be using the three phases of financial data analysis - collect, prepare, and analyze.

## Technologies
The analysis leverages Python 3.7.11 with the following packages:
* [pandas](https://pandas.pydata.org) - for collecting, preparing, and analyzing data using JupyterLab.
* [matplotlib](https://matplotlib.org) - for plotting data on line graphs and box plots.

## Installation Guide
To run the analysis, import the following libraries:
```python
  import pandas as pd
  from pathlib import Path
  %matplotlib inline
```

## Usage and Summary Analysis
The analysis is structured as follows:

1. **Collect data**: Collects the data stored in the Resources folder and stores it in data frames, using the timestamp for an index.

2. **Prepare data**: Prepares the data by dropping records with missing values, removing $ signs, and removing duplicated records.

3. **Analyze data**: Analyzes the data by creating summary statistics for each data frame and plotting data to identify arbitrage opportunities.

4. **Month-wise analysis**: Looks at each month separately and selects three separate dates to represent the most likely days for successful Bitcoin arbitrage.

5. **Key findings**: Provides key findings for each of the three dates selected, including the net arbitrage profit spread and the duration of each opportunity.

6. **Conclusions**: Concludes that the opportunities for Bitcoin arbitrage decreased drastically from January to March 2018, and that the arbitrage opportunities that did exist were short-lived.

7. **Caveats**: Provides caveats to the cumulative profit sums, including the assumption of buying and selling just one Bitcoin at a time and the potential for reinvestment to compound investment returns.

## Contributors
This Notebook was made by Evan Badding with starter code provided by University of denver 

## License
This project is licensed under the [MIT License](https://opensource.org/license/mit/).