# Python API Challenge

# Background
Data's true power is its ability to definitively answer questions. So, let's take what you've learned about Python requests, APIs, and JSON traversals to answer a fundamental question: "What is the weather like as we approach the equator?"
Now, we know what you may be thinking: “That’s obvious. It gets hotter.” But, if pressed for more information, how would you prove that?

# Part 1: WeatherPy

## Generate the Cities List by Using the `citipy` Library
![](WeatherPy/output_data/1.png)

## Requirement 1: Create Plots to Showcase the Relationship Between Weather Variables and Latitude

### Use the OpenWeatherMap API to retrieve weather data from the cities list generated in the started code
![](WeatherPy/output_data/2.png)

### Create a DataFrame with the retrieved weather data
![](WeatherPy/output_data/3.png)

### Create the Scatter Plots Requested

![](WeatherPy/output_data/Fig1.png)

![](WeatherPy/output_data/Fig2.png)

![](WeatherPy/output_data/Fig3.png)

![](WeatherPy/output_data/Fig4.png)

## Requirement 2: Compute Linear Regression for Each Relationship

### Create a DataFrame for the Northern Hemisphere
![](WeatherPy/output_data/4.png)

### Create a DataFrame for the Southern Hemisphere
![](WeatherPy/output_data/5.png)

### Temperature vs. Latitude Linear Regression Plot
![](WeatherPy/output_data/Fig5.png)
![](WeatherPy/output_data/6.png)

![](WeatherPy/output_data/Fig6.png)
![](WeatherPy/output_data/7.png)

Analysis:
- The r-value > 0.7 for both hemispheres shows that there is a strong correlation between the latitude where the city is located and the maximum temperature.
- This correlation can be seen on how the observations are around the regression line.
- The closest the cities get to the equator the highest the maximum temperature is. This is shown with the negative correlation in the northern hemisphere and with the positive correlation in the southern hemisphere.


# Humidity vs. Latitude Linear Regression Plot
![](WeatherPy/output_data/Fig7.png)
![](WeatherPy/output_data/8.png)


![](WeatherPy/output_data/Fig8.png)
![](WeatherPy/output_data/9.png)

Analysis:
- The r-value < 0.3 shows there is a very week correlation between the latitude and the humidity.
- This means there is no relation between the distance to the equator and the city humidity %.


# Cloudiness vs. Latitude Linear Regression Plot
![](WeatherPy/output_data/Fig9.png)
![](WeatherPy/output_data/10.png)

![](WeatherPy/output_data/Fig10.png)
![](WeatherPy/output_data/11.png)

Analysis:
- The r-value < 0.3 shows there is a very week correlation between the latitude and the cloudiness.
- This means there is no relation between the distance to the equator and the city cloudiness.


# Wind Speed vs. Latitude Linear Regression Plot
![](WeatherPy/output_data/Fig11.png)
![](WeatherPy/output_data/12.png)

![](WeatherPy/output_data/Fig12.png)
![](WeatherPy/output_data/13.png)

Analysis:
- The r-value < 0.3 on the northern hemisphere and < 0.5 in the southern hemisphere show there is a very weak and weak correlation respectively, between the latitude and the wind speed.
- This means there is no relation between the distance to the equator and the city wind speed.