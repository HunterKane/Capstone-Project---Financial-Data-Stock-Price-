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


**EDA**
What is the max Close price for each bank's stock throughout the time period?
**Bank Ticker**
- BAC     54.900002
- C      564.099976
- GS     247.919998
- JPM     70.080002
- MS      89.300003
- WPC     58.520000

**Using this returns DataFrame, figure out on what dates each bank stock had the best and worst single day returns**
**Worst:**
- BAC Return   2009-01-20
- C Return     2009-02-27
- GS Return    2009-01-20
- JPM Return   2009-01-20
- MS Return    2008-10-09
- WPC Return   2009-01-20

**Best:** 
- BAC Return   2009-04-09
- C Return     2008-11-24
- GS Return    2008-11-24
- JPM Return   2009-01-21
- MS Return    2008-10-13
- WPC Return   2008-07-16


__Riskiest Stocks for 2015?__

- BAC Return    0.016163
- C Return      0.015289
- GS Return     0.014046
- JPM Return    0.014017
- MS Return     0.016249
- WPC Return    0.012591
__Morgan Stanley has the higest risk factor for 2015__

