# Group Project: Sale of Shares Advisor

"Buy, Hold or Sell?" A common question share holders constantly deal with. <br>

![Image](https://github.com/KRuschmann/Sale_of_Shares_Advisor/blob/master/Buy-Sell-Hold-Image.png?raw=true){ width=50% } <br>

As this decision involves a highly complex procedure that requires a considerable amount of time and expertise, we have tried to incorporate this process into a single tool to reduce the time consuming workload of every single investor. If you are curious to learn more about our approach, we encourage you to read on and experience our Sale of Shares Advisor yourself!

1. [ Group Project Members ](#memb)
2. [ General Information ](#desc)
3. [ Technologies/Setup ](#usage)
4. [ Code Structure ](#code)
5. [ Appendix: Libraries Description ](#app)
6. [ Disclaimer ](#discl)


<a name="memb"></a>
## 1. Group Project Members
- Lucas Jutzi
- Lukas Kevic-Niederer
- Katharina Ruschmann
- Samuel Weber

<a name="desc"></a>
## 2. General Information
This student project "Sales of Shares Advisor" is part of the course "Programming - Introduction Level" by Mario Silic at the University of St. Gallen (HSG). The purpose of this project is a fundamental analysis of publicly listed companies in order to determine whether a stock is efficiently priced and should therefore be purchased. This is based on an automated process of calculating and analyzing future free cash flows (DCF analysis), which is industry standard in the financial sector and many other industries.

<a name="usage"></a>
## 3. Technologies/Setup
- Python version: Python 3.8.5
- JupytherLab: Please refer to https://jupyter.org/install to install JupytherLab.
- Required libraries: ```numpy``` ```pandas``` ```yfinance``` ```pandas_datareader``` ```statistics``` ```datetime``` ```statsmodels.api``` ```matplotlib.pyplot```

In order to properly use our Stock Investing Advisor, it is essential to have installed the above listed libraries prior to running this program. To install the libraries, please use PowerShell in Anaconda with the following commands:

```
$ pip install numpy
$ pip install pandas
$ pip install yfinance
$ pip install pandas_datareader
$ pip install statistics
$ pip install datetime
$ pip install statsmodels.api
$ pip install matplotlib.pyplot
```


<a name="code"></a>
## 4. Code Structure
### Step 0
Prior to getting started it is vital to install and import all the required libraries that are listed in the chapters above. Disregarding this step will lead to an incorrect execution of this program.

### Step 1

The first step is to enter the desired stock ticker (e.g. 'AAPL' for Apple Inc. or 'MSFT' for Microsoft Corporation). Please note that for some smaller companies there is not enough data available to value the stock based on a DCF valuation. In this case, the program will display a corresponding error message.

### Step 2

In this section the program makes some assumptions that are essential for the excecution of the valuation process.


<a name="app"></a>
## 5. Appendix: Lirbaries Description


<a name="discl"></a>
## 6. Disclaimer
This valuation model is based on the anticipation of future free cash flows. As with any intrinsic valuation method, it is essential to bear in mind that valuations are not equally applicable to all businesses. While some companies do not even meet the required criteria (e.g. generating positive cash flows), other companies' values are not directly linked to the generation of free cash flows (e.g. Tesla and other companies that are experiencing hype for various reasons). Therefore, it is important to consider the individual context of each company in order to correctly implement the output of this DCF valuation. The delivered value should never be considered as an isolated basis in any decision-making process.
