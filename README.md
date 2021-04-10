## Weather_API

## How does the weather change across different Latitudes?

#Summary: To the answer the questions above I collected data from over 500 different cities around the world using API calls. Using latitudes, longitudes and the OpenWeatherMap API, I was able to retrieve temperature, humidity, cloudiness, and wind speed. Once I have retrieved the dependent variables from the API, I then plotted each of them against the latitude using Matplotlib scatter plots. I then split the data into northern hemisphere and southern hemisphere to see if there is a difference in correlation between the north and the south.
***All of the  visualizations and the data can be found in the output_data directory. 

# Observations:

1) In the Northern Hemisphere there is a high negative correlation between latitude and max temperature. The further north from the equator you go the lower the temperature becomes. The correlation coefficient is roughly -.84 which is close to -1 (a perfect negative relationship).
2) The scatter plot with the least amount of correlation is the "Northern Hemisphere - Wind Speed (mph) vs. Latitude" with a correlation coefficient of roughly .11. All these comparisons did not have much correlation besides the correlation between the max temperature and latitude.
3) The only linear regression model that fits the data somewhat well is the "Northern Hemisphere - Max Temp vs. Latitude Linear Regression model". The R-squared returned a number around .73 which is close to 1 and shows that it tracks the movement of the data quite well. The same comparison for the southern hemisphere did not give that great of results but I believe it is because there was less data used in the modeling and correlation analysis.

## What would be the top 10 cities to visit based off my ideal weather conditions?

#Summary: I filtered the data from the previous dataset using what I believe to be the ideal weather conditions for vacation. Using Google APIs, I then retrieved the nearest hotel in the cities that I retrieved from the filtered data set. I then created info boxes for the hotel information and plotted the result on a heatmap. Below you can see the results.

 




