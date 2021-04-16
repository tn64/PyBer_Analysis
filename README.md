<!-- Photo by Life Of Pix from Pexels -->
<img src=https://github.com/tn64/PyBer_Analysis/blob/main/Resources/pexels-life-of-pix-7674.jpg>

# PyBer Analysis

## Overview

The scenario for this module is that we have been tasked with creating a summary DataFrame of the ride-sharing data for PyBer. The DataFrame, indexed by city type, is to be used to analyze the data that the company has collected. Additionally we are to prepare a line graph showing the sum of fares for each city type, dispayed by week, over a four-month timeframe. This analysis will summarize how the data differs according to the type of city in order for the decision-makers to make informed decisions for the future of the company.

## Results

The analysis focused on the following areas for the specified period:
- The total number of rides by city type
- The total number of drivers by city tpye 
- The total fares collected by city type
- The average fare per ride/driver per city type

A final graph is presented for "Total Fare by City Type" in order to visualize the data collected.


### Total Ride Data

There is a sigificant difference in the number of rides per city type. Though population size was not considered in the categories. 
- There were 500% more rides in the suburban cities than in rural cities, and 1,300% more rides in urban cities than in rural cities.
- There were 260% more rides in urban cities than in suburban cities.

<img src=https://github.com/tn64/PyBer_Analysis/blob/main/Resources/total_rides_by_city_type.png>


### Total Drivers Data

There are also sigificantly more drivers as the size of the cities increase.
- There were 628% more drivers in suburban cities than in rural cities, and 3,083% more drivers in urban cities than in rural cities.
- There were 490% more drivers in urban citeis than in suburban cities


<img src=https://github.com/tn64/PyBer_Analysis/blob/main/Resources/total_drivers_by_city_type.png>


### Total Fares Data

The trends observed above continued for the total fares collected for each city type.
- 447% more in fares was collected in suburban cities than in rural cities, and 921% more in fares collected in urban cities than in rural cities.
- 205% more in fares were collected in urban cities than in suburban cities.


<img src=https://github.com/tn64/PyBer_Analysis/blob/main/Resources/total_fares_by_city_type.png>


### Average Fare per Ride and Driver Data

The average fare per ride dropped as the size of the city increased. Presumably this was due to the average distance of the ride, however, ride distance was not provided in the data.

<img src=https://github.com/tn64/PyBer_Analysis/blob/main/Resources/average_fare_per_driver_per_city_type.png>

### Total Fare by City Type Data

As demonstrated in the graph below, total fares by city type did not show significant changes over the selected period. All three types of cities experienced a spike in fares during the third weel of February and a corresponding decline the following week. Fares then remained in a range of approximately $500 throughuot the following weeks of the period with urban fares experiencing the most volitility. 

<img src=https://github.com/tn64/PyBer_Analysis/blob/main/Resources/total_fare_by_city_type.png>

## Summary & Recommendations

The following three recommendations.

1. Determine the impact of the number of drivers over time

The total number of drivers for the entire time period was tracked, but not the number of drivers per week or per month. Gathering this information would help to establish how driver attrition or growth affects rides and fares.


2. Examine underlying reasons why fares have not shown consistent growth over time

As the data demonstrates, fares for each type of city have remained in a range over the specified time period. Further analysis of any collected data should be analyzed in order to understand the underlying reasons for this.


5. Examine population and distance related data

Further data should be collected and analyzed regarding the relationship between population, distance of rides, and drivers as a percentage of the population to determine what affect these have on fares.
