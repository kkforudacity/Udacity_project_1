PYTHON LIBRARIES USED

•	pandas
•	matplotlib
•	sklearn.linear_model
•	datetime

PROJECT MOTIVATION

When surveying the internet for different datasets to analyze for the first project of the udacity data science nanodegree, it was interesting to come across the Chicago data portal that stored a wide variety of datasets relating to the city. The data that interested me most in this portal was the data logging taxi trips taken across the city. Each recent calendar year has a full dataset with records of the distinct taxi trips taken through the year with details such as the time and date of the trip, fare, tip paid, company used, pick up and drop off community area. I decided to explore the 2020 calendar year dataset while pairing it with income, population, and square area datasets for the different community areas sourced from other sites. The three questions I decided to explore are:

•	With 2020 as a transition year due to COVID-19, what were the general trends in taxi usage through the year?

•	On some trips a tip was paid while on many others a tip was not. What general factors in the dataset relate to whether a tip is paid?

•	With the median household income, population, and area data on the community areas in the additional datasets, how do these factors relate to the frequency of taxi trips in the different community areas?

FILES USED

chicago_taxi_2020.csv : This is the data that contains the records of all the taxi trips in 2020. It was sourced from the Chicago data portal at:
https://data.cityofchicago.org/Transportation/Taxi-Trips-2020/r2u4-wwk3

chicago_communities.csv : This is the dataset that mapped the commununity area numbers to their names along with their 2020 populations and areas.
The source of this dataset was: https://en.wikipedia.org/wiki/Community_areas_in_Chicago#cite_note-City_basics-9

chicago_income.csv : This is a historical dataset that recorded the median household incomes of the different community areas. It was sourced from:
https://www.chicagomag.com/Chicago-Magazine/April-2006/The-Geography-of-Money/

SUMMARY OF RESULTS

The results generally indicated that the lockdowns in March 2020 had a significant effect on the use of taxi's in the year 2020 with steep declines in trip frequencies and tips paid that never recovered through the rest of the year. The data also showed that the time of day, payment type, and community area had the most significant relation with the tip rate of the variables analysed. The tips paid positively correlated with early night trips, credit card and mobile payments, and trips in O'Hare, Garfield Ridge and the loop. Population and the historical median houselold income were both found to moderately positively influence the number of trips in the community areas 


