# APIs

#Methodology


1. Used the starter code to get the list of cities
2. Set the random number of cities to be searched for lat, long to 2500 (so that one has enough cities to look up in openweathermap)
3. Once collected, pass them on to the openweathermap API (this further reduces the number of cities) 
4. Once a list of cities are there, selected the top 500
5. Based on the list, drew the charts for different weather parameters.


#Conclusions

1. There are more cities in the northern hemisphere than southern, which is evident in the clustering. Though random lat/ long were chosen, the openweathermap API returned higher number of values for northern hemisphere
2. As hypothesized, it is hotter towards the equator. As the latitudes merge towards the equator, we can observe increase in temperature
3. There is not a strong correlation between humidity and latitude, however a case can be made for higher humidity (60 to 100) in a -40 to 60 range of latitude
4. A higher cloudiness is recorded in the northern hemisphere

