# exchange-rate-analysis
This project fetches exchange rates from an API and performs data analysis to find the best and worst exchange rates and calculate the average exchange rate for the month.

### Architecture
![architecture drawio (3)](https://github.com/Veera-Pipuri/exchange-rate-analysis/assets/162418085/0942f243-afb6-49ff-a745-13f6120c8d95)

Architecture Overview
1. Exchange Rates API (Source):
This component is responsible for connecting to any exchange rates API to retrieve the exchange rates of Australia to New Zealand for the past 30 days.
2. Jupyter Notebook:
A Jupyter Notebook is used for data processing and analysis. It includes the following sub-components:
    API Request: Handles the request made to the Exchange Rates API.
    Load Data: Fetches the exchange rate data for the specified duration.
    Data Analysis: Manages expected issues, handles any missing data, and performs data analysis.

### Approach
1. **Connect to the Exchange Rates API**: Connect to any exchange rates API to get the exchange rates of Australia to New Zealand for the past 30 days.
2. **Preprocess the Data**: Manage expected issues, handle any missing data.
3. **Perform Data Analysis**: Find the best and worst exchange rates for the given period. Calculate the average exchange rate for the month.


