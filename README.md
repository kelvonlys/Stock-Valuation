# Stock-Valuation
This algorithm applies different financial models to calculate the reasonable price of a single stock in order to provide a better way of investing in a stock.

# Objective
The purpose of writing this alogrithm is to calculate reasonable price for stocks in order to determine a buy signal when underpriced and a sell signal when overpriced.

# Valuation Model
Different financial valuation model including Price-To-Earning ratio, Price-To-Sales ratio and Price-to-fund-from-operations ratio. The reasonable price is calculated as follow:  
reasonable price = 5 year averaged ratio * trailing 12 months per share value  

The industry average is also take into consideration when applying financial ratios to a stock.


# Visualisation
The graph below shows reasonable price of a REITS. After research, Price-to-fund-from-operations seem to be the best method of valuing a reits since it takes into consideration the growth of its underlying assets.   

From the graph below, it also shows that the price of REITS follows the curve of PFFO (blue line) for most of the time.
![alt text](https://github.com/kelvonlys/Stock-Valuation/blob/main/valuation.png)

