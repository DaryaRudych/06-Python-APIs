# Weather Analysis with Python APIs

## Background
Whether financial, political, or social – data's true power lies in its ability to answer questions definitively. Taking what I've learned about Python requests, APIs, and JSON traversals, I want to answer a simple but fundamental question: "What's the weather like as we approach the equator?"

Now, you may be thinking: "Duh. It gets hotter..."

But, if pressed, how would you prove it?

In this project, I created a Python script to visualize the weather of 500+ cities across the world of varying distance from the equator. To accomplish this, I utilized a simple Python library, the OpenWeatherMap API, and a little common sense to create a representative model of weather across world cities.

 A series of scatter plots showcases the following relationships:

#### Temperature (F) vs. Latitude
![Alt text](https://github.com/DaryaRudych/06-Python-APIs/blob/master/TempVsLatitude.png)

#### Humidity (%) vs. Latitude
![Alt text](https://github.com/DaryaRudych/06-Python-APIs/blob/master/HumidityVsLatitude.png)

#### Cloudiness (%) vs. Latitude
![Alt text](https://github.com/DaryaRudych/06-Python-APIs/blob/master/CloudinessVsLatitude.png)

#### Wind Speed (mph) vs. Latitude
![Alt text](https://github.com/DaryaRudych/06-Python-APIs/blob/master/WindVsLatitude.png)


## Findings:
1. It seems like there is no correlation between latitude and humidity,latitude and wind speed, latitude and cloudiness. However, latitude does determine temerature. The plot "Max Temperature vs Latitude" shows that temperatures drop the further an area is from the equator, which is due to the curvature of the earth.
2. Maximum temperatures are observed between 20th and 30th degree of latitude and not the equator, which is something that requires further research.
3. Most of the data points on all of the plots are located between 0 and 90 degree latitude, which makes sense and indicates that there are more cities in northern hemisphere than in southern.
