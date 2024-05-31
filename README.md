# Philvolcs-2024-Earthquake-Visualization
This data is about earthquake events in year 2024 and their characteristics, such as date and time of occurrence, latitude, longitude, depth, magnitude, and location description.

##Discussion
Date - Time (Philippine Time): The date and time of the earthquake event in Philippine Time.
Latitude (ºN) and Longitude (ºE): The geographical coordinates of the earthquake event.
Depth (km): The depth at which the earthquake occurred below the Earth's surface.
Magnitude: The magnitude of the earthquake, typically measured using the Richter scale.
Location: A description of the location of the earthquake event.

##Targets
Determine the strongest earthquake magnitude recorded in the dataset.
Analyze Magnitude Distribution: Calculate the distribution of earthquake magnitudes and identify any patterns.
Visualize the average depth of earthquakes over time using a heatmap.
Determine the number of earthquakes per month from January to May 2024, and can you provide the exact count of earthquakes for each month.
Location-Based Analysis: Investigate the distribution of earthquakes based on location descriptions to identify earthquake-prone areas.

##Analysis Plan
1. Identify the strongest earthquake magnitude recorded in the dataset.
Find the earthquake record with the highest magnitude in the dataset.
Use pandas to locate the row in the dataset corresponding to the earthquake with the highest magnitude.

2. Analyze Magnitude Distribution: Calculate the distribution of earthquake magnitudes and identify any patterns.
Create a histogram or kernel density plot of earthquake magnitudes to visualize the distribution.
Determine the shape of the distribution and look for any notable peaks or patterns.

3. Visualize the average depth of earthquakes over time using a heatmap, with the x-axis representing the day and the y-axis representing the month
Extract the month and day from the date for grouping.
Calculate the average depth of earthquakes for each month and day.
Create a heatmap to visualize the average depth over time.

4. Count earthquakes monthly from January to May 2024 and provide the exact counts for each month.
Extract the month from the date for grouping.
Count the number of earthquakes for each month.
Present the exact count of earthquakes for each month

5. Identify the Most Seismically Active Areas.
Count the number of earthquakes for each location description.
Use a barplot to visualize the distribution of earthquakes based on location descriptions.
