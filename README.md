# PyBer_Analysis
ride-sharing app company data analysis

## Overview of the analysis

Performing an exploratory analysis and creating visualizations using ride_data.csv and city_data.csv to understand  access to rideshare services in urban , suburban and rural city types.

**Purpose**
The purpose of this exploratory data analysis is to identify key ride sharing metrics by type of city and create a graphical representation of the total weekly fares based on the city types which will help improve access to ride sharing services and determine ride affordability.

## Results

 - The total rides, total drivers, total fares,  and driver, and total fare by city type were obtained using the groupby function along with the sum , count function.
 - The  average fare per ride and driver  was obtained by dividing the total fares per city type by the total ride/drivers per city type. 
 
![The formatted summary DataFrame showing the “Total Rides,” “Total Drivers,” “Total Fares,” “Average Fare per Ride,” and “Average Fare per Driver” by city type](https://static.bc-edx.com/data/do-v2/m5/img/data-Module-5-Challenge-Challenge_Summary_DataFrame.png)




As shown in the data frame above:-

 - The rural cities had the highest average fare per driver and ride.
 - The urban cities had the lowest  average fare per driver and ride.
 - The high fares observed in the rural cities was due to the low number of total rides and total drivers in those cities.

![The average weekly fare for each city from January 1, 2019 to April 28, 2019.](https://static.bc-edx.com/data/do-v2/m5/img/data-5-1-challenge-average-fare-each-city.png)

As shown in the multiple line graph above:-

 1. The urban cities had the highest total fare within the months of January to April 2019 followed by the rural cities.
 2.  There is a larger use of PyBer ridesharing in urban cities.
 3.  There are more drivers in urban cities than rural cities.
 4.  As a result, the majority of PyBer's revenue occurs in urban cities.
 4. In addition, although the available data is limited to 2019, the Urban cities might also benefit from more ride allocation within the months of January to April as this will help meet the demands for rides in those months , increase revenue and enhance affordability.
 5.  Drivers in rural cities are earning more than drivers in urban cities. This could discourage discourage potential drivers from working with PyBer given the low average fare per driver.
 6.  There is another opportunity for further analysis to determine other factors that are contributing to the high ride costs in rural cities and low driver fares in urban cities. Perhaps, travel distance is a key factor.



## Summary
Based on the overall analysis of the ride and city data a number of key disparities stick out. The largest of which is the rural metrics. Every metric measured in the analysis of the city types has rural cities at the bottom of the pile. Below are a few suggestions to help improve the bottom line, i.e., total profits.

 - In summary, the drop in the number of ride usage in the rural    cities within the months of January to April, 2019 could be due to    the low number of available rides and drivers in those cities and    allocating more rides & drivers to the rural cities will most likely    reduce average fare per ride & driver which will invariably boost    ride affordability. 
 
 - On the other hand, the costs for using PyBer is greater among riders in rural cities than urban cities. This could discourage    potential riders from using PyBer given the high average fare per    ride.If we give new riders some promotional offers to encourage them to use PyBer.Also,a bonus received on taking X no of  rides would increase the total rides and overall profits.
 - The  largest disparity between the Urban ,Suburban and Rural cities, is the number of drivers in each. Looking at a summary of the driver count data you can see that the average number of drivers in rural cities is nine to four times less per city than in urban and suburban cities, respectively. Enticing more drivers to drive in these areas could improve overall profits.
 - One way to entice drivers to drive in rural areas would be to promote area bonuses. Give drivers an incentive to drive in these areas by adding a small multiplier to the driver’s payout for each ride in the area. For example, adding a 1.1X multiplier for each ride a driver gives in rural areas would bring more drivers into the area. More drivers in the area would in turn result in more rides, and more overall revenue.

