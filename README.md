# Bike-Sharing-Demand
Bike Sharing Demand_EDA and ML<br>
1-Importing library (Numpy-Pandas-Matplotlib.pyplot-Seaborn-DateTime_Sklearn)<br>
2-Load and preparing data<br>
--Features:<br>
*datetime - hourly date + timestamp  
*season -  1 = spring, 2 = summer, 3 = fall, 4 = winter 
*holiday - whether the day is considered a holiday
*workingday - whether the day is neither a weekend nor holiday
*weather - 1: Clear, Few clouds, Partly cloudy, Partly cloudy 
2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist 
3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds 
4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog 
*temp - temperature in Celsius
*atemp - "feels like" temperature in Celsius
*humidity - relative humidity
*windspeed - wind speed
*casual - number of non-registered user rentals initiated
*registered - number of registered user rentals initiated
*count - number of total rentals

3-EDA<br>
--Split time and date from 'datetime' column<br>
--Add 'weekend' column to check it's effect on bike renting<br>
--Calculate counts for workingday, weekend and holiday. This is for check effect of these parameters on bike renting.<br>
4-Data Preprocessing<br>
5-Strorytelling - Visualization<br>
6-Train your model (Regression)<br>
*Linear Regression<br>
*Multiple Regression<br>
*KNN Regressor<br>
*Decision Tree Regressor<br>
*Random Forest Regressor<br>
