# surfs_up
Analysis weather for a surf shop business

# Overview
The purpose of this analysis is to detect temperature trends in the island of Oahu where the surf and ice cream business is going to be. The code is going to be designed to be easily refactorable so that it can be used for different locations.

# Sources

- Data : [hawaii sqlite database](https://github.com/Donik22/surfs_up/blob/main/hawaii.sqlite) 

- Software : Python 3.9.4, anaconda 1.7.2 , git version 2.30.1.windows.1

# Results

The analysis was run in June and December. In the bulleted lists below the difference between the temperature during the mentioned price will be highlighted.
- Count of (June,December) = (1700,1517)
- Average Temperature of (June,December) = (74.94 ℉ ,71.04 ℉) 
- June Minimum and Maximum Temperature = (64 ℉,85 ℉)
- December Minimum and Maximum Temperature = (56 ℉,83 ℉)

# Summary

## Data limitations
This Analysis is based only on temperature for a given date. For a surf shop business, many other factors can be considered like (customer behavior, Popularity of the area, political/global events, etc.). 


## Aditional Analysis
From the data, we collected we can predict that June would be the best month to stock up on supplies in the store given the temperature is higher in June. The scatter gives us more opportunity to track the daily temperature during a given month.

![june plot](https://github.com/Donik22/surfs_up/blob/main/Resources/June%20scatter%20plot.PNG)

December witnessed a lower temperature which is not as attractive for tourists, Giving the owner a chance to cut his losses and minimize expenses. 

![December plot](https://github.com/Donik22/surfs_up/blob/main/Resources/December%20scatter%20plot.PNG)

## Conclusion

Nonetheless, Temperature is a huge factor in predicting the profitability of the business. in conclusion, June seems to be the best month for a surf and ice cream shop. like the scatter plots below show the weather in December can go as low as 56 ℉ which is not ideal for surfing.
