# Coursera_Capstone
IBM Applied Data Science Capstone Project

#The Battle of Neighborhoods
#Analysis of Chicago Suburbs for A Prospective Restaurant Location

#Introduction
Chicago is the third most populous city in the United States and has diverse population. Chicago’s 58 million domestic and international visitors in 2018 made it the second most visited city in US when compared to New York City’s 65 million visitors. Chicago is famous for large number of regional specialties (cuisines) which reflect the city’s ethnic and working-class roots. Large number of world-famous chefs have their restaurants in the City of Chicago.

#Business Problem
Our Client is running a fine dining restaurant in downtown Chicago; client wants to expand their operations into the suburbs of Chicago. Top 20 Suburbs of Chicago (Suburbs with population more than 5000) are been considered as prospective locations for the new restaurant. Based on analysis of various data collected from United States Census Bureau and Foursquare API, ideal suburb will be identified for the new restaurant.

#Data
1) Top 20 suburbs of Chicago metropolitan area (In the Data set Suburbs with population less than 5000 has been excluded) are based on the information available in www.niche.com
Ref:https://www.niche.com/places-to-live/search/best-suburbs/m/chicago-metro-area/
2) Suburbs Population data (Population estimates, July 1, 2019, (V2019)) is obtained from United States Census Bureau website for the suburbs obtained from niche website.
Ref: https://www.census.gov/quickfacts/fact/table/US/PST045219
3) Each suburbs Latitude and Longitude is retrieved using OpenCage Geocoder Python package.
4) Foursquare API is used to explore different venues and frequencies in each suburb, data retrieved will be helpful in clustering the suburbs based on their development.
Foursquare API Developer Access: https://developer.foursquare.com/
Table 1: Suburb’s Top 10 Venues
Methodology
Methodology includes:
1. Data Retrieval, exploration, and wrangling
2. Performing K-mean C
