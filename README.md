# PyBer_Analysis

## Purpose:

1. Create line, bar, scatter, bubble, pie, and box-and-whisker plots using Matplotlib.
2. Add and modify features of Matplotlib charts.
3. Add error bars to line and bar charts.
4. Determine mean, median, and mode using Pandas, NumPy, and SciPy statistics.

# Overview
After completing an exploratory analysis for PyBer, a ride-sharing business, a deeper dive into reviewing the data by city type was requested by the CEO. The scope of work includes using Python, Pandas, and Matplotlb to create a summary DataFrame and a multi-line graph of the total weekly fares for each city type: Rural, Suburban, and Urban.

# Results:

# Summary

After merging two data sets and using the groupby() functions, the fare per ride and fare per driver averages were calculated resulting in the summary DataFrame by city type.


<img width="455" alt="Deliverable1" src="https://user-images.githubusercontent.com/109055148/209457147-f00674e3-12a8-473e-99b3-e8d607db3bd9.png">


1. The Urban city type had more total drivers than total rides, which had a dramatic impact on the average fare per ride and average fare per driver. The Urban drivers had the lowest average fare per ride and earned significantly less than the Rural drivers.

2. The Rural city type had the least number of total drivers giving way to having the highest average fare per driver even though the ratio of total rides to total drivers is equivalent to the Suburban city type.

# Total Fare by City Type

From the summary DataFrame, the data was pivoted into a new DataFrame, and then grouped by weeks to show the total fares by city type.


![PyBer_fare_summary (1)](https://user-images.githubusercontent.com/109055148/209457158-c7af86f7-b9fe-476b-8826-daee3875d805.png)

1. All three city types start to rise to a peak at the end for February. For the Urban city type, that oscillating peak lasts through April, while the other city types wane in the month of March.

2. The Rural city type increases again leading into the month of April. The Suburban city type starts to peak again at the end of April, while the Rural city type drops off.


# Summary 

## Recommendations: 

a) The results of the summary DataFrame could be due to Urban city types being more compact, which collects a lower average fare per ride, while Rural city types are more spread out, which would collect a higher average fare per ride. To test this theory, PyBer should work to include mileage distance data as part of the data collection process and analysis.

b) Because there are more total drivers than total rides in the Urban city types, the Urban drivers may not have enough work to support themselves. PyBer may want to consider investing advertising dollars in the Urban city types to increase the total rides or risk losing Urban drivers.

c) If PyBer were to invest into advertising dollars in the Urban city type, the next question is when would ads be the most effective? After reviewing the Total Fare by City Tpye graph, the end of February kicks off the increase in total fares and would be a good time to launch an advertising campaign, which would also strategically help the other two city types.
