# Capstone-Project---Financial-Data-Stock-Price-
Focus on bank stocks and see how they progressed throughout the financial crisis all the way to early 2016. https://en.wikipedia.org/wiki/Financial_crisis_of_2007–2008

**Main goal of project: Practice your visualization and pandas skills.**

__Data__:

We need to get data using pandas datareader. We will get stock information for the following banks:
- Bank of America
- CitiGroup
- Goldman Sachs
- JPMorgan Chase
- Morgan Stanley
- Wells Fargo

** Figure out how to get the stock data from Jan 1st 2006 to Jan 1st 2016 for each of these banks. Set each bank to be a separate dataframe, with the variable name for that bank being its ticker symbol. This will involve a few steps:**

__Note__:
- Use datetime to set start and end datetime objects.
- Figure out the ticker symbol for each bank.
- Figure out how to use datareader to grab info on the stock.



Method:
- Importing
- Inspecting
- Cleaning
- Using datareader
- Visualizing data with various graphs
- Analyzing data findings

Get the Data
- Use pandas to directly read data from Google finance using pandas.

**Make sure to install datareader
Install latest development version:

- pip install git+https://github.com/pydata/pandas-datareader.git or
- git clone https://github.com/pydata/pandas-datareader.git cd pandas-datareader python setup.py install
