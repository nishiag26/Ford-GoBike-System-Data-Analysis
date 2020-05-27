Project: FordGoBike TripData Analysis
Ford GoBike, previously known as Bay Area Bike Share, is a bike share system currently implemented in San Francisco, East Bay, and San Jose.
 The data describes all the trips taken from operation's rebranding as Ford GoBike (June 28, 2017) until the end of the year (December 31, 2017)

Main Findings from exploratory analysis are:
1.There are more number of Subscribers than Customers using the bikes.
2.More number of Users have used the bikes on Tuesday and Wednesday.
3.More Users must have returned the bikes on same day which they took the bike.
4.Large distances are covered by very less number of people, Users have booked the bikes mostly for short distances.
5.Customers have booked the bikes for more duration than Subscribers.More number of Customers have not returned the bikes on same day than the number of Subscribers.
6.Both Subscriber and Customer have used for similar distances on average with one outlier for each user type i.e with distance in range of 60 to 70 km.
7.Users have used bikes for more duration for shorter distances range 0 to 10 km approx. 0 km here means that Starting and End Points are same.
8.Few Customers on Friday have covered longer distances and few Subscribers have covered longer distances on Thurday and Tuesday.


By refining the graphs in multivariate distribution helped in explanatory analysis.

Conclusions are:

1.Out of total number of bike users, 409230 are Subscribers and 110470 Customers.

2.Subscribers have mostly picked up bikes on Tuesdays and Wednesdays, Customers have mostly picked up bikes on Saturday and Sundays.

3.More number of Customers have returned the bikes on next day, which shows that they have kept bikes for longer duration than the number of Subscribers.

4.Few Customers have covered long distance on Friday for short duration of time and few Subscribers have covered long distance on Thurday and Tuesday with long duration of time.

5.Both Customer and Subscriber have covered short distances( refer to the same start and end points calculated as 0 km in the analysis) but have booked bikes for longer duration. Few of customers have covered longer distances and have booked bikes for short duration only.

6.Both Subscriber and Customer have used bikes for shorter distances range 0 to 10 km approx.(0 km here means that Starting and End Points are same).


Resources:
1.Referred for making multivariate plots - https://datascienceplus.com/seaborn-categorical-plots-in-python/
2.Plottting regplot - https://seaborn.pydata.org/generated/seaborn.regplot.html
3.For Axes transformation - https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.ylim.html