# PyPoll_Challenge
##Overview
the purpose of our analysis is to create a summary dataframe that will show ride sharing data by city type(Rural,Urban & Suburban). Once we have found our data we have  created  multiple line graph that shows total weekly fares by each city type. we first pulled our data is by using the pandas Groupby() function with the count() and sum () to get the total number of drivers,rides and fares by city type. Once we pulled this information and assigned it to functions we were able to calculate our average fare per ride and driver. Once we had all of that information together we were able to format into a newdata frame and re-format the columns. In the second part of this excercise we used the pivot() and resample function to create a multiple line graph that shows the total fares for each week by city type between the months of January & April of 2019.
#Results
through analysis and aggregation of PyBers ride sharing data

<img width="485" alt="pyber_summary_frame" src="https://user-images.githubusercontent.com/93894919/148714193-ea63498e-2d77-4511-b875-c3f957da3dbd.PNG">

By reviewing the summary we can see that there are several key findings including:

Rural cities has the least amount of drivers, rides and total fares.
Urban cities have the most amount of drivers, rides and total fares.
Suburban cities are in the middle having the 2nd most drivers, rides and total fares.
Although Rural cities see the least amount of drivers,rides & fares the have the highest average of fare per ride and fare per driver.
Although the Urban cities command the most drivers, rides and fares they have the lowest average of fare per ride and fare per driver.
##Summary
From our data we are able to tell what kind of fares will be commanded based on what city type the passenger is catching a ride in. Although we didn't explore every individual city we still have a great grasp on what fares will look like from week to week based on city type which is enough information decide on rates that will need to be charged after we can classify what type of city the consumer lives in. In conclusion we can effectively say that a rural area will command a higher fare because there are fewer workers that will come to this area, the travel time and distance is most likely longer making the average fare per ride & driver the most out of all city types.

 
