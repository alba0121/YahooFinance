# YahooFinance

## Processed financial information from Yahoo Finance

This Viewer uses the API of Yahoo Finance, through yahoo_fin which has to be installed in Python.

As part of the functionalities, the viewer displays options to look prices, volume and balance sheets from companies or indexes. If the user decides to check historical data, the Viewer displays graphs and allows to download information and storage in csv files.

The code can be found: https://github.com/alba0121/YahooFinance/blob/main/yahoo_code.

The original source is: https://finance.yahoo.com/, and the documentation can be found: https://theautomatic.net/yahoo_fin-documentation/ and https://pypi.org/project/yfinance/.

## Background

The user needs to install yahoo_fin:

pip install yahoo_fin

In case that the user already has  the package, it can be updated:

pip install yahoo_fin --upgrade

Additionally, it is requiered requests_html

pip install requests_html

## Display

1. The user run the code.

2. The first options is look for companies or indexes. Some tickers are suggested in the command displayed, however, the code is not limited to them. It is important to know that the tickers are different depending on the source, for instance if the information is looked in other systems as Bloomberg or Reuters, the format of the tickers are different.
For the purpose of this project, a few tickers are showed in the code to help the user to display information.

3. The second option is introduce single or historical data, if the user chooses single data, the last available value is showed. It means that the last price changes everyday.
If the user chooses historical data, the user have to specify the range of date desired, the format must be followed.

4. Once the user chose the option historical and entered the range of date, a graph is displayed with the historical information. It should be closed to continue with the next option.

5. An option to download the information in a csv file is displayed.
