# Supply-Chain-Optimization-Using-Python
A low capacity and high capacity plant across 5 countries are considered and a linear programming model is built to determine the total lowest costs for satisfying consumer demand across all countries, based on various constraints. Data visualization is done and interactive widgets are used to compare different scenarios.

## Assumptions made for additional data:
Storage costs are 10% of fixed costs per year. So taking 10% of fixed costs and dividing by 30 (fixed costs are given per month) to get the storage costs per unit per day.

Assuming cargo ships run on diesel. 1 liter of diesel gives out 2640g of CO2. 

https://ecoscore.be/en/info/ecoscore/co2

So taking the distance between each of the country ports and multiplying with 10.82. 10.82 = 2640 * 3.8/962 where the average mileage of a cargo ship is 576 miles per gallon. So 1 km of movement in a cargo ship gives out 10.82g of CO2 per ton weight. The CO2 emissions are calculated likewise.

Assuming shipping happens only through sea freight. The following are the ports considered for shipping:

Port of New York - USA

Port of Hamburg - Germany

Port of Tokyo - Japan

Port of Santos - Brazil

Port of Mumbai - India
   
Assuming a standard delivery lead time of 3 days between the same country, delivery lead times of each location is taken based on the average time taken to go from 1 of the above ports to the other + 3 days for moving within the country.

## Reference Code: 
https://github.com/samirsaci/supply-chain-optimization
