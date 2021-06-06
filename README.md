# PyBer_Analysis - Overview of the analysis:
The purpose of this analysis was to put the matplotlib / data visualization work we learned through the module 5 in to practice.

We were tasked with creating an analysis on 2019 Pyber Ride Share data for the CEO, V. Isualize. This analysis would be used to inform future strategy for the Pyber company.

# Results

## Summary Dataframe

Throughout the analysis and module challenge, we created a summary dataframe to investigate differences between city types. This can be found below:

<img width="532" alt="Screen Shot 2021-06-06 at 2 53 51 PM" src="https://user-images.githubusercontent.com/46773181/120941343-050df080-c6d7-11eb-9482-b88150aa1a39.png">

The total rides for each city increases as we move from less populated city types (Rural) to more populated (Urban). This is to be expected, as those people that live rurally are more likely to own and rely on their own vehicles for transport.

Total drivers follows the same relationship to city types as total rides. With less drivers, there will be less rides taken. Drivers will try and position themselves in more densely populated areas (suburban / urban) in an attempt to maximize the amount of trips they are taking.

When looking at fares, it is interesting to see that although the total fares for Rural represents the smallest amount of the three city types, the average fare per ride and average fare per driver is negatively correlated. However, we understand that rural areas will likely mean longer trips which means these trips will be more profitable when looking at these metrics vs. urban / suburban.

Although the average fare per ride / driver is smaller for urban / suburban, the volume of rides occuring in these areas is far greater than rural. So, even though the rural rides seem the most profitable on a per ride basis, there currently isn't the volume to make it a sensible market of focus.

## Time Series of Fares Early 2019

We also created a time series for the total fare amount for each city type from January 1, 2019 to April 29, 2019. This can be found below:

<img width="891" alt="Screen Shot 2021-06-06 at 2 54 19 PM" src="https://user-images.githubusercontent.com/46773181/120941351-1525d000-c6d7-11eb-95d9-196ee4638dad.png">

As we look at this, we see that the Urban city type brings in the most revenue, with Suburban and Rural following in respectively. Urban and Suburban city types have trended up over the beginning of 2019 while Rural has remained relatively constant.

If we wanted to understand whether these trends are seasonal (and fares for more densely populated areas increases as we move through the year), then we should select a greater period of time (and across multiple years) to view the sum of fares.

# Summary

In summary, after viewing the results from the analysis, I have compiled a few recommendations for the business stakeholders of Pyber:
1. Investigate ways to increase volume amongst rural -- if PyBer wants to see the rural market make up a larger % of overall revenue, then we need to find ways to increase the volume. As these are the most profitable rides when looking at average fare per driver / ride, increased volume could bring in significantly more revenue. Some suggestions here could be increasing the number of drivers (perhaps low volume is a result of low supply) or focussing on rural markets that yield more volume
2. 
