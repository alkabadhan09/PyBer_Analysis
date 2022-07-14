# PyBer Analysis
## Overview
### Background
In this module, we work at PyBer, a Python based ride sharing app, as Data Analysts and we are given a project which consists of cleaning, inspecting, and visualizing the ride-sharing data using Pandas, Jupyter Notebook, and Matplotlib. We visualize the data using a variety of charts that showcase the relationship between the type of city, the number of drivers and riders, as well the percentage of total fares, drivers, and riders by the type of city. PyBer's goal is to use our analysis and visualizations to help PyBer improve access to ride-sharing services and to determine affordability to underserved neighborhoods.
### Purpose
The purpose of this challenge is to create a summary DataFrame of ride-sharing data by city type, which is either Urban, Suburban, or Rural. We are also instructed to show the total weekly fares for each city type using Matplotlib and creating a multi-line graph. We also submit a written report summarizing how the data differs by city type and how those differences can be used by decision-makers at PyBer. 
## Results
#### PyBer Summary DataFrame: 

![Screenshot 2022-07-14 123322](https://user-images.githubusercontent.com/107225715/179068458-cedf52d9-e207-4797-9386-bf446156e743.png)

Looking at the PyBer Summary DataFrame, we notice that PyBer is most in demand in urban cities as total rides, drives, and fares are significantly higher in those cities. If we look at the numbers for rides, total rides across the three city types are 2375. Urban cities make up 68.4 %, suburban cities make up 26.3%, and rural cities make up a mere 5.3% of that number. Similarly, out of 2973 drivers across all city types, 80.9% are urban, 16.5% are suburban, and 2.6% are rural. Following the same trend, out of $63538.64 total fares across all city types, 62.72% are from urban cities, 30.5% are from suburban cities, and 6.8% are from rural cities. With the average fare per ride and per driver, the trend is reversed as the rural cities are charging themost per ride and per driver with $34.6 and $55.5 respectively. Suburban cities are still in the middle, charging an average of $31 and $39.5 respectively for per ride and driver. Urban cities, however, are the cheapest for the rides as the average fare per ride is $24.5 and average fare per driver is $16.6.

#### Multi-Line Chart:

![ride](https://user-images.githubusercontent.com/107225715/179090832-b8a1f81a-28f3-4936-a457-dd3f0d7d4d4d.png)

On the multi-line chart, we see weekly dips or peaks in the line graphs from the months of january to april of 2019. This further support our conclusions from the summary DataFrame as we see that  urban cities (yellow line) generated the most fare. Suburban cities (red line) are balanced between urban and rural cities, and PyBer is the least in demand in rural cities (blue line).

## Summary
As we saw in the results from the dataFrame and the chart, there are some disparities between all three city types. I would recommend the CEO to look more into why the costs for rides are higher in the rural cities as that might be why PyBer is generating the least amount of revenue there. It might be longer distance, less population, or something along those lines but doing more research might result in positive changes. I would also recommend looking into why the drivers are being paid less in urban cities even though they are generating the most revenue for PyBer as less pay might result in less drivers in the future. Another business recommendation would be to maybe have a different business models for the three different city types as looking at the results, the current model is doing well only in urban areas. The model can be taylored according to the needs of customers from different city types and would be beneficial to PyBer.
