# PyBer_Analysis


**Overview**

This challenge had us analyze ridesharing data using two different csv files. We got to use the Python and Pandas skills we learned to load in two csv files, read them, and then merge them into one DataFrame. Then using MatPlotLib and Pandas again create a pivot table and line graph that shows the total weekly fares for each of the city types. 

During the first deliverable we got the total rides, total drivers, and fares by city type, total amount of fares by city type, and then get the average fare per driver for each of the city types; rural, suburban, and urban. Then we created a new dataframe using all these new parameters we found.

During the second deliverable we created a new dataframe that only inlcuded the city type, date and sum of the fares. Then we created a pivot table for 2019-01-01 to 2019-04-28, for city type looking at fare sums. We changed the date index to a datetime datatype. Finally we created a new dataframe that looked at weekly fare sums for the time frame specfied for each city type, and then outputted a pivot table that matched that. 

**Results**

The results are as follows; Urban had the highest number of rides, total drivers, and highest amount of fares, but lowest average fare per ride and per driver. 
Rural had the lowest total fares, total rides and total drivers but had the highest average fare per ride and average fare per driver. 
This makes sense because in rural areas there are less people spread out over a larger area so rides are longer but more expensive when compared to a urban area where rides are generally shorter and quicker, leading to more rides but not as much charged. 

![Screen Shot 2022-12-21 at 8 54 00 PM](https://user-images.githubusercontent.com/118235205/209062611-2112ca02-a29d-4b0b-a18b-d42c25f6966f.png)

![Screen Shot 2022-12-21 at 9 19 55 PM](https://user-images.githubusercontent.com/118235205/209062659-362f04ac-47a1-46a8-bbd1-cf871e942959.png)

-There is an increase after the new year in both suburban and urban areas as people are traveling from holidays (two and from parties and back to work). 


**Summary**
Three recomendations to the CEO would be to:
1. Increase the number of drivers in rural areas to try to lower the average price per ride.
2. Increase the price per ride in the urban areas to that even though there are more rides the drivers are making more per fare.
3. Try to get more rides between city types to increase the average cost per ride; i.e. rural to urban, suburban to urban or rural, and urban to suburban or rural. This means that drivers would have a chance to get more of the average fare in that specific city type. 



