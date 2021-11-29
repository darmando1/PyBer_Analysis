# PyBer Analysis
## **Overview**
Identifying trends utilizing the python pandas and matplotlib library. Through customization of dataframes and graphs we perform analysis on multiple data sets and combine data sets. We are able to identify driver and fare trends based on city types and date ranges.
## Results
Utilizing a combined dataframe we see that there are significantly more drivers in an Urban area versus a Rural area but the Average Fare per Ride is more than $10 higher in the rural areas.

![Pyber Summary DF](https://github.com/darmando1/PyBer_Analysis/blob/main/Pyber_fare_summary.png)

It may be possible to infer that due to both low demand in drivers and riders for rural areas it is important to increase prices in said areas to incentivise drivers. Likewise with Urban areas being saturated by both drivers and riders, it may be less necessary to increase prices as drivers will acquire more riders. Another data point is identifying whether or not rides increase or decrease based on date or more importantly potentially by season. There may be more rides requested in urban areas during the summer versus during the winter as many people may prefer to stay indoors during the winter. This may be identified utilizing the "resample()" function of pandas.
![Pyber_Summary_ByWeek](https://github.com/darmando1/PyBer_Analysis/blob/main/Pyber_Summary_byWeek.JPG)
Above we can identify a trend of fares increasing across the city types as the dates get closer to summer and warmer weather.
## Recommendations
Based on the above data points there may be three recommendations to maximize profits:
- Rural areas appear to lack both demand in drivers and riders. The increased fares may be due to either longer distances traveled or increased fares. It may be beneficial to acquire drive length to identify whether or not the riders are requesting rides to further areas or specific landmarks such as airports. Based on the above data it may be better to incentivise drivers with one time bonuses, decrease the cost of the fares, and incentivise more riders.
- Fares decrease within all city types during colder date ranges. To incentivise continued revenue and growth even during "off-season" time frames it may be beneficial to offer coupons or discounts for riders to airports as travel may occur earlier in the year due to holidays.
- Another important statistic is the length of downtime by driver. Do drivers in rural areas wait significantly longer per ride versus drivers in urban areas? How can we incentivise rural drivers to continue to meet demand without excessively charging potential new customers?
