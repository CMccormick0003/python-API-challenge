# Mapping Cities with Ideal Weather

## Scope: 
Use APIs to identify cities with a close hotel where weather conditions meet prespecified parameters

## Tools: 
Python, Pandas, APIs keys, scipy.stats, matplotlib, OpenWeatherMap API, GeoApify API

![image](https://github.com/CMccormick0003/python-API-challenge/assets/120672518/edfd55c3-7531-422b-a71a-50d83a7143ba)

![image](https://github.com/CMccormick0003/python-API-challenge/assets/120672518/5a803292-f1e9-4261-a3db-44e819931f38)

![image](https://github.com/CMccormick0003/python-API-challenge/assets/120672518/8f037893-77e6-45fb-8214-a1260a6471f0)

![image](https://github.com/CMccormick0003/python-API-challenge/assets/120672518/93a97f5a-9fc7-41fe-b369-f39911895ea5)

## Compute Linear Regression for Each Relationship
![image](https://github.com/CMccormick0003/python-API-challenge/assets/120672518/17b46f80-514d-4d11-aeab-5bdb33c8969a)

![image](https://github.com/CMccormick0003/python-API-challenge/assets/120672518/26ba1273-2af7-4b8b-bb6d-4b542a2c4007)

![image](https://github.com/CMccormick0003/python-API-challenge/assets/120672518/2b934554-b58d-42c1-bfef-cede7f83193a)

![image](https://github.com/CMccormick0003/python-API-challenge/assets/120672518/4a753725-fdbd-4e42-b507-7330345a85d4)

![image](https://github.com/CMccormick0003/python-API-challenge/assets/120672518/db531b1e-7001-49c8-9aeb-0ffeb27a6783)

![image](https://github.com/CMccormick0003/python-API-challenge/assets/120672518/2338d4ff-cdcc-474b-a2a6-cc6f86be6974)

![image](https://github.com/CMccormick0003/python-API-challenge/assets/120672518/0e454f32-57f2-40f9-ba77-1cd41c6b3c8a)

![image](https://github.com/CMccormick0003/python-API-challenge/assets/120672518/02346c48-2720-480a-9cfd-b66d69d0508a)

## All Cities in the cities_data_df
![image](https://github.com/CMccormick0003/python-API-challenge/assets/120672518/aa772f09-be96-42dc-a368-d041cd160e4e)

This dataframe was refined to include only cities with ideal weather as temperature between 21 and 27 C, wind speed less than 4.5 m/s and no clouds.
For each, the Geoapify API was used to find the first hotel located within 10,000 metres of the city's coordinates (hotel_df).
The hotel name and  country were added to the map and appear if you hover over each city in the map.¶

![image](https://github.com/CMccormick0003/python-API-challenge/assets/120672518/3f1962db-e2af-4303-9895-b66c4b2b3d77)

## Source
Starter code for Python was provided by the Rutgers bootcamp.  Real-time data for weather and cities were obtained from the APIs.

