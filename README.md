# Pyber Analysis
---
## Overview
The purpose of this project is to use Python's pandas, numpy, and matplotlib to analyze Pyber's ride share data over a certain period of time, as well as create visualizations showing the difference between certain metrics. The main areas of focus that are analyzed in this project are:
- Average fares per ride
- Amount of rides per city type
- Number of drivers per city type
- Fares per city type

---
## Results
#### Drivers per City Type
The number of drivers differs greatly across the city types with urban having the most number of drivers, susburban second, and rural last. Simply put, the lower the demand in the city type, the smaller the supply of drivers there are.

Urban: 2405

Suburban: 490

Rural: 78

#### Rides per City Type
Following a similar trend, the number of rides per city type is highest in urban cities, with suburban cities second and rural third. The more people there are in a city, the more rides occur.

Urban: 1625

Suburban: 625

Rural: 125

#### Fares per City Type
Overall, the total fare values for each city type continues to follow the same trend, with urban cities generating the most total fares, followed by suburban, then rural third. This is due to the higher number of rides resulting in a higher total fare value.

Urban: $39,854.38

Suburban: $19,356.33

Rural: $4,327.93

However, the average fare per ride by city type produces an inverse relationship, where the less rides there are, the higher the average fare is. Rural cities had the highest average fare, followed by suburban in second, and urban last.

Urban: $24.53/ride

Suburban: $30.97/ride

Rural: $34.62/ride

--- 
## Summary
Based on this analysis, I have developed three recommendations to optimize Pyber's ride-share business.
1. The percentage of total rides that are in rural cities (5.3%) is greater than the percentage of total drivers that drive in rural cities (2.6%). This could mean that there is a shortage of drivers in the rural areas and the total demand is not being met. I would recommend trying to place more drivers in the rural areas to increase the total rides there.
2. Similarly to the rural cities, the percentage of total rides that are in suburban cities (26.3%) is greater than the percentage of total drivers that drive in suburban cities (16.5%). This could once again signify a demand that is not being met, so I would recommend trying to place more drivers in the suburban cities as well.
3. Inversely, the percentage of total rides that are in urban cities (68.4%) is less than the percentage of total drivers that drive in urban cities (80.9%). This could mean that there is a surplus of drivers in the city, and not enough demand. I would recommend trying to attract more riders in the urban areas to meet this supply of drivers. One way to do this would be to advertise the lower average fare per ride in urban areas.
