# all-stocks-analysis

All stocks analysis based on the year

In this challenge, the refactored code will run analysis for all stocks returns based on the year of slelection. This is achived through looping the stocks data and collecting required information in a single pass. The 2017 year analysis reveals that the DQ stock had highest retuns of  199.45% whereas TERP was dropped by 7.2%.

The refactored code layout:
1. Findout the year of analysis (input box)
2. Activate the All Stocks Analysis Worksheet and create column headers
4. Activate the year of analysis worksheet 
5. Define the arrays and Initialize the tickerIndex before For loop.
6. First For loop, initialize the ticker Volumes to zero
7. Second For loop, iterate ticker index and calculate Total Daily Volume and Return for all tickers using conditions on starting and ending prices
8. Thrid For loop, Collect output values of tickers, tickerVolumes, tickerEndingPrices on the defined cells
9. Format the output
10. Fourth For loop, based on the conditions color the cells
