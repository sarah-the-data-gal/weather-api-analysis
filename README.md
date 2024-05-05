# weather-api-analysis

# Background
For this project, I am using Python, APIs, and JSON traversals to explore the question: "What is the weather like as we approach the equator"? While most of us understand that as we approach the equator, temperatures increase, this Python script will use the power of Data to definitively answer this question. 

# WeatherPy 
Temperature vs. Latitude: As expected, temperatures tend to increase as we approach the equator, with the Northern Hemisphere experiencing colder temperatures compared to the Southern Hemisphere.
Humidity, Cloudiness, and Wind Speed vs. Latitude:  Latitude has little to no influence on cloudiness and a weak, positive correlation with humidity and wind speed. Cloudiness remains scattered across latitudes, indicating no significant correlation. The influence of latitude on wind speed is minor but slightly more pronounced in the Southern Hemisphere, possibly related to seasonal variations.

The linear regression analyses provided quantifiable measures of these relationships, reinforcing the observed trends.

Plots to Showcase Weather Relationships with Latitude
Latitude vs. Temperature
Latitude vs. Humidity
Latitude vs. Cloudiness
Latitude vs. Wind Speed
Linear Regression Analysis
Compute linear regression for each relationship
Separate plots into Northern and Southern Hemispheres
Include linear regression lines, model formulas, and r values

# VacationPy
Ideal Weather Conditions: By defining criteria such as optimal temperature ranges, low wind speeds, and clear skies, I identified cities with ideal weather conditions for vacationing.
Hotel Recommendations: Utilizing the Geoapify API, I located hotels near selected cities meeting the desired weather criteria, facilitating vacation planning.
Key Tasks
Map Creation
Display city points on a map, with point sizes corresponding to humidity levels
Ideal Weather Conditions
Define desired weather conditions (e.g., temperature range, wind speed, cloudiness)
Hotel Search
Use Geoapify API to find hotels near specified coordinates for each city
# Conclusions 
The WeatherPy and VacationPy projects demonstrated the utility of data analysis in understanding weather patterns and leveraging weather data for practical applications like vacation planning. Insights from these projects can inform decision-making processes for travelers and researchers, highlighting the value of data-driven approaches in various domains.
