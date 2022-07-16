# PyBer_Analysis
## Overview of the analysis
PyBer is python-based ride-sharing app company. The goal of this analysis is two-fold: first, analyzing the ride-sharing data from January to April 2019 to create a summary DataFrame with the following metrics: total rides, total drivers, total fares, average fare per ride, and average fare per drive. All are categorized by city types; second, creating a multiple-line graph that shows the total weekly fares for each city type by using Pandas and Matplotlib. The analysis will summarize how the data differs by city type and how those differences can be used by PyBer decision-makers. 

## Results
The generated PyBer summary DataFrame shows the disparity of ride-sharing data among the three different city types.
![pyber summary DataFrame](/analysis/pyber_summary.png)
* The number of total rides in the uraban cities is about 13- and 2.6-times more than the rural and suburban cities, respectively. 
* The number of total drivers in the urban cities is about 31- and 5-times more than the rural and suburban cities, respectively. 
* The total fares collected from the data set is $63,538.64. Urban cities make up 62.7%  of total fares collected, while rural and suburban cities make up only 6.8% and 30.5%, respectively. 

On the contrary, both the average fares per ride and per driver are much higher in rural citeies comparing to urban and suburban cities.
* Average fare per ride in rural cities costs about 10.5% more than suburban cities and 29.1% more than urban cities. 
* Average fare per driver is fairly low in urban cities. Urban fare is 58% cheaper than suburban fare and 70% cheaper than rural fare.

![multiple-line chart of total fares for each city type](/analysis/Fig8.png)
The multiple-line chart shows the urban cities had the highest while rural cities had the lowest total fares for each week. The weekly total fares of all city types reach the first peaks at the end of Feburary, then both the urban and rural cities reach the second peaks at the beginning of April. In general, all the graphs follow the similar trends throughout the four months, except for the suburban cities, there's a sharp increase from mid to the end of April.

## Summary
Three recommendations are made based on the above analysis summary results and trends shown in the graph:
*  In order to narrow the huge gap of rides between densely populated and less populated cities, some targeted promotions/campaigns are needed to increase the number of Suburban and rural riders.
*  The average fare per driver shows the rural fare is extremely higher than the urban and suburban fares, which indicates there's a shortage of rural drivers. So PyBer might need to increase more drivers in rural areas to optimize its profits.
*  The weekly total fares of all city types chart shows the similar trends reaching the first peaks at the end of Feburary. PyBer could analyze further on the data during this special period. Is it because of increased new riders or more current riders? What campaigns/promotions make such increase companywide? 

 


