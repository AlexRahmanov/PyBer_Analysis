# Background

V. Isualize has given you and Omar a brand-new assignment. Using your Python skills and knowledge of Pandas, you’ll create a summary DataFrame of the ride-sharing data by city type. Then, using Pandas and Matplotlib, you’ll create a multiple-line graph that shows the total weekly fares for each city type. Finally, you’ll submit a written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer.

# verview of the analysis:

The purpose of our analysis is to create a summary dataframe that will show ride sharing data by city type(Rural,Urban & Suburban). Once we find our data we are going to create a multiple line graph that shows total weekly fares by each city type. How we first pulled our data is by using the pandas Groupby() function with the count() and sum () to get the total number of drivers,rides and fares by city type. Once we pulled this information and assigned it to functions we were able to calculate our average fare per ride and driver. Once we had all of that information together we were able to format into a newdata frame and re-format the columns. In the second part of this excercise we used the pivot() and resample function to create a multiple line graph that shows the total fares for each week by city type between the months of January & April of 2019.

# Summary

From our data we are able to tell what kind of fares will be commanded based on what city type the passenger is catching a ride in. Although we didn't explore every individual city we still have a great grasp on what fares will look like from week to week based on city type which is enough information decide on rates that will need to be charged after we can classify what type of city the consumer lives in. In conclusion we can effectively say that a rural area will command a higher fare because there are fewer workers that will come to this area, the travel time and distance is most likely longer making the average fare per ride & driver the most out of all city types.
