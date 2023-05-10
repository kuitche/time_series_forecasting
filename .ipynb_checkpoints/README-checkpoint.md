# Background
With over 200 million users, MercadoLibre is the most popular e-commerce site in Latin America. As a growth analyst, we've been tasked with analyzing the company's financial and user data in clever ways to help the company grow. So, we want to find out if the ability to predict search traffic can translate into the ability to successfully trade the stock.

# What we're creating
In a bid to drive revenue, we’ll produce a Jupyter notebook that contains our data preparation, analysis, and visualizations for all the time series data that the company needs to understand. We’ll use text and comments to document your findings. Specifically, this notebook contains the following:

* Visual depictions of seasonality (as measured by Google Search traffic) that are of interest to the company.

* An evaluation of how the company stock price correlates to its Google Search traffic.

* A Prophet forecast model that can predict hourly user search traffic.

* A plot of a forecast for the company’s future revenue.

# Summary of the findings

* MercadoLibre released its financial results in May 2020. The traffic of May 2020 is higher than the monthly median; meaning the traffic increases in May 2020 compared to *half* of other months. 

* The average Search traffic appears to be very low between the 6th and the 12th hour every day. The 1st to 3rd hour, and the 23rd and 24th hours appear to see the highest average search traffic each day of the week.

* The average search traffic tends to increase from week 46 thru 51,then a big drop in week 52

* The Search trends and revenues time series do not indicate a common trend that’s consistent with the narrative that new customers and revenues increased in the first half of 2020. Specifically, the plot did not show a substantial increase in the search trends

* There is a substantial negative correlation between lagged search traffic and the stock volatility. The positive correlation between lagged search traffic and the stock price returns is not as pronounced.

* The near-term forecast shows a slight dip in the search trends

*  Midnight exhibits the greatest popularity; Tuesday gets the most search traffic; and the lowest point for search traffic in the calendar year is in October

* Forecast of the total sales for the next quarter:    
- Worst Case: 887.7   
- Best Case: 1050.5   
- Most Likely: 969.6

