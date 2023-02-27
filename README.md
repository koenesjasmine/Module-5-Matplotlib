# Ride Share with Matplotlib

## Project Overview
V. Isualize has given us the task of analyzing some PyBer rideshare data to better understand performance. 

The current data existing in two separate data sets the first task to is to make this easier to read by merging the two frames. 

![Raw_Data_Screenshot](insert img here)

![Raw_Data_Screenshot](insert img here)


As seen above, the common factor is city, so merging the two sets with this column


## Challenges
One of the hurdles in this challenge was the amount of the drivers. The driver count by city is listed in the ride data, and for each city on every entry it lists the full count of drivers for the city. Doing a sum on this column results in tons of duplicates. to correctly refine this we need to trim down a dataframe to only a unique set of cities with corresponding type and driver count. Once this wass donem we were able to do a groupby and sum the driver count. 

## Data Summary Results
Rhe below table of results has been charted for easily analysis. 

![Raw_Data_Screenshot](insert img)
we can see that Urban cities have far more total rides as well as drivers.
on average it is more expensive for a rider in the rural areas than urban areas. 
conversely it is more lucrative for drivers in rural areas likely due to the relative shortage compared to total riders. 


![Raw_Data_Screenshot](insert img)
Overall revenue remains constant for all city types between January and May. 
Urban revenue is always the highest volume, followed by Suburban and then Rural ,icj further below. 

## Conclusion
Revnue remains highest in urban cities and lowest in rural areas. Revenue has not significnatly changed between January 2019 and May 2019. Drivers are likely to make more money on average (per driver) in rural areas. this may be useful to signal to drivers to help balance out supply and demand. having more drivers may also increase demand for ridership in the area, but that is purely speculation at this stage. 