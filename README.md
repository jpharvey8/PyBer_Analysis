# PyBer_Analysis
## Overview of analysis 
The purpose of this analysis was to explore and create visualizations using rideshare data to help improve access to rideshare services for three different city types: urban, suburban and rural. The goal was to compare total weekly fares for each city type and give recommendations for addressing disparities among city types. 

## Resources 
Data source: city_data.csv, ride_data.csv
Software: Python 3.7.7, Anaconda Navigator, Jupyter Notebook, Pandas, and Matplotlib libraries 

## Results 
The figure below shows a PyBer summary DataFrame that includes the Total Rides, Total Drivers, Total Fares, Average Fare per Ride, and Average Fare per Driver for the rural, suburban and urban city types. 
<img width="297" alt="2022-01-03" src="https://user-images.githubusercontent.com/92167429/147984108-cf6e2809-1111-4097-ab20-ba6b4cc5e8c1.png">

This DataFrame shows urban cities rely more on rides for transportation and have the most drivers. As a result, the urban city type brings in the most revenue, $39,854.38 in total fares. The rural cities has the least amount of rides and total drivers, resulting in the lowest revenue, $4,327.93. Although rural cities have the lowest revenue, they have the highest fare per ride which may be due to the average number of miles it takes to get from one destination to another. Urban cities have the lowest average fare per ride. Another metric that is included in the DataFrame is the average fare per driver. Drivers in rural cities make almost 3 times more than a driver in an urban city. 

A multiple line chart was also created to help visualize the Total Fares by City Type from January 1, 2019 to April 29th, 2019. 
![Pyber_fare_summary](https://user-images.githubusercontent.com/92167429/147988481-7fde5ca9-bc7c-44b3-8ad9-1861618eb46f.png)

The three different city types can be distinguished by the three different colors: Rural = blue line, Suburban = coral line, Urban = gold line. We can quickly tell that Urban city types had the highest total fares and rural areas had the least. All three lines also have an upswing in fares towards the end of Febuary which may indicate increased demand. 

## Summary 
Here are the recommendations for addressing any disparities among the city types: 
- Urban cities are the best performing city type and account for most of the revenue for the company. Therefore, investments should continue to be made to acquire greater profits for PyBer in the future. 
- Suburban cities are the middle performing city in all of the metrics we analysed so more investments can be focused on Urban and rural city types. 
- Rural cities had the least amount of rides and lowest fares among all city types but the average fare per ride was the highest for this city type. If the number of riders could be increased in these cities, this could greatly increase the revenue for the company. PyBer should focus their investments in marketing for these city types. 
