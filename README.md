# ARIMA-Model-for-EUR-JPY-Exchange-Rates
This repository contains a Python script that retrieves historical EUR/JPY exchange rates from the Twelve Data API and applies an ARIMA (Autoregressive Integrated Moving Average) model to predict future exchange rates.

## Installation

To run the script, please follow the instructions below:

1. Clone the repository to your local machine.

2. Install the required dependencies by running the following command:
   
pip install pandas numpy matplotlib seaborn requests scipy statsmodels

3. Obtain an API key from the Twelve Data website (https://twelvedata.com/) and replace the placeholder `api_key` in the script with your actual API key.

## Usage

1. Run the script using Python 3:
   
   python eur_jpy_exchange_rate_prediction.py

2. The script will retrieve the historical EUR/JPY exchange rates for the last 60 days from the Twelve Data API and save the data to an Excel file named `eur_jpy_data_15min.xlsx`.

3. The script will analyze the data, perform ARIMA modeling, and generate predictions for the test data. The predicted values will be plotted alongside the actual values.

4. Additionally, the script will generate additional plots such as probability plots, autocorrelation function (ACF) plot, partial autocorrelation function (PACF) plot, and a kernel density estimation (KDE) plot of the residuals.


Please note that the script assumes a stable internet connection to retrieve data from the Twelve Data API.

Feel free to modify the code to experiment with different parameters or customize the analysis as needed.



