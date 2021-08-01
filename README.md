


# Financial Planning Tools
#### Using API's and Simulations

---
Two financial planning tools. The first determine if a credit union member has enough financial reserve for an emergency fund by using visualization tools. The second makes predictions to determine the performance of a retirement account in 30 years using historical data and a Monte Carlo simulation.  

---

## Technologies

This prodject uses Python 3.7 with the following packages:
* ### **os** - Allows inreaction with the operating system
* ### **requests** - Enables ability to send HTTP request
* ### **json** - Transfers data into a easy-to-read format
* ### **pandas** - A package of intuitive data analysis tools
* ### **dotenv** - Loads environment variables from an env file
* ### **alpaca_trade_api** - Creates access to realt-time data
* ### **MCForecastTools** - Uses random variables oo run simulations to make predictions
* ### **%matplotlib inline** - Enable ability to plot data

---

## Installation Guide

### First, install the following:
    
    pip install alpaca-trade-api

### Sign-up for an Alpaca account:
   
    https://app.alpaca.markets/signup

### Create a .env file and copy alpaca keys to that folder:

    ALPACA_API_KEY = "YOUR_API_KEY_HERE"

    ALPACA_SECRET_KEY = "YOUR_SECRET_KEY_HERE"

Then import the following:
    
    import os
    import requests
    import json
    import pandas as pd
    from dotenv import load_dotenv
    import alpaca_trade_api as tradeapi
    from MCForecastTools import MCSimulation
    %matplotlib inline
    
---

## Usage

Determine the current value of a credit member's cryptocurrency wallet and stock portfolio, in the planner use data along with monthly income to determine if there is enough savings to build an emergency fund into their financial plan. In the second planner, create a Monte Carlo simulation and compare data of 30 years to various other years, sample numbers, and ratios of stock to bond in portfolio to determine which factors yeild the best retiment plan. 

 
---

## Contributors

A.Nansamba Ssensalo
[LinkedIn](www.linkedin.com/in/a-nansamba-ssensalo)

---

## License

[![License](https://img.shields.io/badge/License-Boost%201.0-lightblue.svg)](https://www.boost.org/LICENSE_1_0.txt)
