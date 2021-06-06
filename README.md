# PyBer_Analysis - Overview of the analysis:
The purpose of this analysis was to put the matplotlib / data visualization work we learned through the module 5 in to practice.

We were tasked with creating an analysis on 2019 Pyber Ride Share data for the CEO, V. Isualize. This analysis would be used to inform future strategy for the Pyber company.

# Results

Throughout the analysis and module challenge, we created a summary dataframe to investigate differences between city types. This can be found below:

<img width="532" alt="Screen Shot 2021-06-06 at 2 53 51 PM" src="https://user-images.githubusercontent.com/46773181/120941343-050df080-c6d7-11eb-9482-b88150aa1a39.png">

The total rides for each city increases as we move from less populated city types (Rural) to more populated (Urban). This is to be expected, as those people that live rurally are more likely to own and rely on their own vehicles for transport.

Total drivers follows the same relationship to city types as total rides. With less drivers, there will be less rides taken. Drivers will try and position themselves in more densely populated areas (suburban / urban) in an attempt to maximize the amount of trips they are taking.

When looking at fares, it is interesting to see that although the total fares for Rural represents the smallest amount of the three city types, the average fare per ride and average fare per driver is negatively correlated. However, we understand that rural areas will likely mean longer trips which means these trips will be more profitable when looking at these metrics vs. urban / suburban.

Although the average fare per ride / driver is smaller for urban / suburban, the volume of rides occuring in these areas is far greater than rural. So, even though the rural rides seem the most profitable on a per ride basis, there isn't the volume to make it a sensible market of focus.

We also created a time series for the total fare amount for each city type from January 1, 2019 to April 29, 2019. This can be found below:

<img width="891" alt="Screen Shot 2021-06-06 at 2 54 19 PM" src="https://user-images.githubusercontent.com/46773181/120941351-1525d000-c6d7-11eb-95d9-196ee4638dad.png">

