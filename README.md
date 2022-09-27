# Pyber_Analysis
Analysis for PyBer, a ride-sharing app company valued at $2.3 billion. Im going to analyze all the rideshare data from January to early May of 2019 and create a compelling visualization using Jupyter Notebook, Pandas, Numpy and Matplotlib libraries.

# Assignment
Using Python skills and knowledge of Pandas, create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, create a multiple-line graph that shows the total weekly fares for each city type. The main query we are looking, is to know how the data differs by city type and how those differences can be used by decision-makers at PyBer.

# Analysis :
In a first approach to the database provided by PyBer, we were able to observe that the greater the number of rides, the greater the number of drivers but at lower fares. In particular, it was observed that urban cities have a large number of rides and drivers, however, the fares used are lower than those observed in rural cities; which, despite having few rides and few drivers compared to urban and suburban cities, have higher rides fares.

![image](https://user-images.githubusercontent.com/43974872/192641837-75d32b3b-a8fb-446d-9d86-fed6a727e10a.png)

Regarding the number of rides, indeed, rural cities have the lowest number, with urban cities being the main clients of PyBer. In the same sense, we find that the number of drivers is low in rural cities, since these have a lower number than urban cities; which is linked to the fact that they also have a smaller number of drivers, so it has a lot to do with the number of rides requested.

![Fig2](https://user-images.githubusercontent.com/43974872/192642399-f3e18619-ee46-4601-b2f8-ddd937a81472.png)
![Fig4](https://user-images.githubusercontent.com/43974872/192643474-2cb4bb1f-c679-4c9a-9162-ae74838d824a.png)

Contrary to fares, rural cities have higher fares than urban cities. Therefore, rural cities should not be ruled out as potential clients for PyBer.

![Fig3](https://user-images.githubusercontent.com/43974872/192642726-4ba25e29-1c80-40a5-bb59-47f4c9ec1f5b.png)


The analysis carried out also shows that when counting the total number of trips by type of city, urban cities are the main ones requesting a trip, followed by suburban cities and lastly, rural cities.
![Fig5](https://user-images.githubusercontent.com/43974872/192645766-2bba4dc2-d2b2-451f-8604-ec1ccc378e20.png)


When analyzing the total number of rides requested, it was found that urban cities continue to be the cities with the highest demand, since 68.4% of the total number of rides requested come from these cities.
![Fig6](https://user-images.githubusercontent.com/43974872/192646230-62b095f1-f6fc-4062-85b7-dc470e8e508a.png)

Therefore, it is also the urban cities that have the highest percentage of drivers fromm all the cities.
![Fig7](https://user-images.githubusercontent.com/43974872/192646442-6281d544-46e3-4381-9b19-8f707fe007b1.png)

# PyBer Summary

Now, after the previous analysis, we carry out a more detailed one.

Where a comparative table was made to be able to observe first-hand the differences between the cities.
In the first place, in effect, urban cities have a greater number of trips, drivers and fares, even when they are the rides with the cheapest average fares; and the lowest fare per driver.

![image](https://user-images.githubusercontent.com/43974872/192647598-1c99a896-4ce7-4054-984f-fd40cc9eba84.png)


In the summary comparative table, we see that the suburban cities, although they only have 26.3% of the total rides (625 rides), have a return of 30.5% for their fares ($19,356.33 USD). In other words, with less than a third of total rides and only with a sixth of the total drivers (490 drivers), suburban cities made a total fare of $19,356.33 USD, so the average of fares for rides and for driver are higher than those observed in urban cities. That is, with far fewer drivers and far fewer rides, they got higher fares per driver and per ride.

However, rural cities present the highest averages fares observed than any other type of city, both for drivers and per ride. However, there are so few rides made that the total fare is much lower than in other cities.

## Total Fare by City Type

In the next chart, we can see that urban cities have higher total fares, followed by suburban cities and finally rural cities. However, each peak represents a week, in that sense, we can see when there is greater demand for rides. In all three types of cities, the third week of February is a week with the highest demand, so in that week PyBer could could plan a campaign to take advantage of the increase in rides in all cities.

![PyBer_fare_summary](https://user-images.githubusercontent.com/43974872/192651947-9d919ca2-2d9c-47b6-b478-6dc5ccf87172.png)


# Business recommendations to the CEO for addressing any disparities among the city types.
1. Carry out specialized campaigns by city. 
2. For urban cities, the third of February, the first and third week of March.
3. For suburban cities, the third week of February, the first and second week of April.
4. For rural cities, the third week of february, and th last week of march.
5. To get higher rates in urban cities, PyBer they could make higher fares per driver.
