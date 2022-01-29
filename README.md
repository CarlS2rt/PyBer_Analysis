# PyBer Ride Data Analysis

## Purpose

The purpose of this project is to analyze ride-sharing data by city type, summarizing the differences by city type as it relates to drivers, rides, and fares. From the summarized results, suggestions can be made to decision-makers and stakeholders on how to best generate growth and revenue for PyBer.

## Ride-sharing data:

Results for the ride-sharing data can be broken into several categories to analyze the differences among the three city types presented in the data.

### Total rides:

Overall, the total rides per city skewed heavily toward urban cities while rural cities had significantly fewer rides and percentage of overall rides as shown below. 

![](https://raw.githubusercontent.com/CarlS2rt/PyBer_Analysis/main/analysis/Fig6.png)

![](https://raw.githubusercontent.com/CarlS2rt/PyBer_Analysis/main/analysis/Fig2.png)

From this data, we can see that the majority of rides are concentrated in the higher-populated urban zones, and rural cities have much fewer rides overall.

### Total drivers:

Similarly to the total rides data, we can see from the charts below that the total count of drivers also skewed significantly toward urban cities in both total drivers and the percentage of total drivers. 

![https://raw.githubusercontent.com/CarlS2rt/PyBer_Analysis/main/analysis/Fig4.png](https://raw.githubusercontent.com/CarlS2rt/PyBer_Analysis/main/analysis/Fig4.png)

![](https://raw.githubusercontent.com/CarlS2rt/PyBer_Analysis/main/analysis/Fig7.png)

Again, the data shows that the majority of drivers, like rides, are concentrated in urban areas with higher populations.

### Average and total fares:

Overall, the total of all fares shows urban areas with the most fare revenue and rural with significantly less revenue as a percentage of the whole. The average fare for each city type also showed some interesting tendencies as shown below:

![](https://raw.githubusercontent.com/CarlS2rt/PyBer_Analysis/main/analysis/Fig3.png)



![](https://raw.githubusercontent.com/CarlS2rt/PyBer_Analysis/main/analysis/Fig5.png)

The average fare for each city type not only shows that urban areas have lower fares on average, but the average fare shows a relatively low amount of deviation. In contrast, the average fare in rural areas is higher and has significantly more deviation. This is demonstrated in the IQR; for the urban cities it is $3.16 while rural cities have an IQR of $5.13.

### Average fare per ride and total rides:

The data below shows the relationship between city type and the average rider fare. The circle size below also correlates with the driver count per city.

<img src="https://raw.githubusercontent.com/CarlS2rt/PyBer_Analysis/main/analysis/Fig1.png"  />

From this data, two correlations emerge. First, there is a positive correlation between city type and total rides in that the larger the city, the greater the number of rides. Second, there is a negative correlation between city type and the average fare in that the average fare decreases as the city size increases. The first, positive correlation also applies if we consider the total drivers by city.

### Total weekly fare by city type:

The data below shows the total weekly fare by each type of city over a third of a year. Based on this, urban cities overwhelmingly have the largest weekly fare revenue than any other city type. 

![](https://raw.githubusercontent.com/CarlS2rt/PyBer_Analysis/main/analysis/PyBer_fare_summary.png)

## Summary

There is a direct correlation between the demand for a ride-share and the average cost of a ride-share. The more rides and drivers, the less the ride will cost. From the above data, the following recommendations can be put forward to PyBer leadership:

- Increase the number of available drivers in rural and suburban areas to decrease the average cost.
- Decrease the number of available drivers in urban areas to increase the average cost. 
- It would also be beneficial to analyze the total distance traveled by city type to determine if there is a relationship between distance and cost, particularly if one city type demonstrates a tendencies to travel greater distances. 

