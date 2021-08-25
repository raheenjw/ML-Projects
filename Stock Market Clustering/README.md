![stock](https://user-images.githubusercontent.com/77233162/130778281-f43e3dda-9dcf-40ed-99ed-9f7081a561a8.jpg)

## Project Overview

In this project we are going to train a k-means clustering algorithm to group companies based on their stock market movements over a 2-year period. The goal of the project will be to find similarities amongst companies that we might otherwise not be able to detect. To do this, the k-means clustering algorithm will produce labels that assign each company to different clusters.

We will also perform principle component analysis for dimensionality reduction.

## Data Overview

The data used here is of 24 major companies.The data itself has been collected from yahoo finance using data reader.

pandas_datareader extracts data from various internet sources into a DataFrame. Currently, the following sources are supported:
- Yahoo! Finance
- Google Finance
- World Bank
- Google Analytics and few others

### Companies used:
'Amazon': 'AMZN',

'Apple': 'AAPL',

'Walgreen': 'WBA',

'Northrop Grumman': 'NOC',

'Boeing': 'BA',

'Lockheed Martin': 'LMT',

'McDonalds': 'MCD',

'Intel': 'INTC', 

'IBM': 'IBM',

'Texas Instruments': 'TXN',

'MasterCard': 'MA',

'Microsoft': 'MSFT',

'General Electrics': 'GE',

'American Express': 'AXP',

'Pepsi': 'PEP',

'Coca Cola': 'KO',

'Johnson & Johnson': 'JNJ',

'Toyota': 'TM',

'Honda': 'HMC',

'Exxon': 'XOM',

'Chevron': 'CVX',

'Valero Energy': 'VLO',

'Ford': 'F',

'Bank of America': 'BAC'

### Parameters related to stocks:

- High : Highest price during the day.
- Low : Lowest price during the day.
- Open: Opening price of the day.
- Close: Closing price of the day.
- Volume: Total number of shares of stock traded during the day.
- Adj Close: The closing price is amended to account for any corporate actions to give the ‘Adjusted closing’ price.












