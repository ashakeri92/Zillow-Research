# Zillow-Research-Analysis
by: Armun Shakeri

### Overview and Business Problem

The goal of this analysis is to identify the top 5 zipcodes for our client to invest in. The team is not familiar with the Texas housing market therefore we will incororporate coefficients of variance to help filter most risk appropriate counties. The results from this analysis will provide them with the forecast of the next 10 year mean house value in the top 5 ZipCodes as well as ROI in 1 year, 3 years, 5 years, and 10 years.


### Data

The dataset for this analysis was gathered from Zillow Research, and contains median home sales price in 1,293 individual ZipCodes from 2000-01-31 to 2022-08-31. Each row represents a unique ZipCode indexed with RegionID, and contains other location info as well as median housing sales price for each month. 

### Methods

To begin analysis we first calculated the average ROI for all counties in Texas and narrowed the list down to the top 10 ZipCodes by selecting the top ZipCodes with highest average ROI in each county. To be mindful of black swan events such as housing bubbles and recessions we used the coefficient of variation to take risk into consideration. This technique is very common within finance to determine how much volatility is assumed in comparison with the amount of return expected from the investments. We also selected data in the top 30-70 quartiles to add some variation. 

For prediction we ran 3 models, Random Walk, ARIMA, and SARIMAX. Out of the three we selected the SARIMAX model which performed the best to forecast the average predicted home values for each of the top 10 ZipCodes for the next 10 years. 

### Analysis


### Conclusion
