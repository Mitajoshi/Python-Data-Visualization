# Python-Data-Visualization

## Overview
The assignment involves analyzing weather patterns in cities relative to their proximity to the equator. WeatherPy utilizes the OpenWeatherMap API and Python scripting to collect and visualize weather data through scatter plots and linear regression. VacationPy then uses this data to plan vacations, creating map visualizations based on humidity levels to narrow down ideal destinations with specific weather conditions.

## Purpose
The assignment aims to showcase Python coding skills in accessing and visualizing weather data, uncovering patterns between latitude and weather variables. Additionally, it demonstrates practical applications by using the gathered data in VacationPy to plan vacations, helping users find optimal destinations based on desired weather conditions. The integrated approach provides both insights into weather patterns and real-world utility for travel planning.

![image](https://github.com/Mitajoshi/Python-Data-Visualization/assets/142932546/913bf8ff-9be6-49ce-9d28-a3545f176863)

![image](https://github.com/Mitajoshi/Python-Data-Visualization/assets/142932546/1558c091-ace8-4326-b346-201ec4422a1f)


## Instructions
For this assigment, we have two code files committed to this repo:
•	WeatherPy.ipynb
•	VacationPy.ipynb
And api_keys.py file(not commited to the code) is updated in gitignore file.

1.	For weather challenge, we are analyzing the weather data for a list of cities and for each city, fetching following weather details:
  •	Latitude
  •	Longitude
  •	Max Temp
  •	Humidity
  •	Cloudiness
  •	Wind Speed
  •	Country
  •	Date
2.	Exporting  the City Data into a cities.csv file in output folder.
3.	Plotting scatter plots and linear regression charts between weather variables(temperature,humidity ,cloudiness,speed plot) and latitude to analyze the relationship between them. Detail analysis is mentioned in the code.
<img width="451" alt="image" src="https://github.com/Mitajoshi/Python-Data-Visualization/assets/142932546/ddf971db-f29e-40ec-bf8a-3650bcf03965">
<img width="451" alt="image" src="https://github.com/Mitajoshi/Python-Data-Visualization/assets/142932546/afd25473-3459-4b42-8c35-35ba00cdf539">
<img width="442" alt="image" src="https://github.com/Mitajoshi/Python-Data-Visualization/assets/142932546/3c4edd10-0086-421f-85a4-722d883148af">
<img width="451" alt="image" src="https://github.com/Mitajoshi/Python-Data-Visualization/assets/142932546/46b24fe5-c877-4fce-862d-83c5b26c1777">
<img width="455" alt="image" src="https://github.com/Mitajoshi/Python-Data-Visualization/assets/142932546/f3d21fcc-6fa9-41a5-992c-4d8958d00b1f">
<img width="434" alt="image" src="https://github.com/Mitajoshi/Python-Data-Visualization/assets/142932546/0184ffdd-464c-485d-a14e-076c0664f5d1">






-For VacationPy,
.  getting the data from cities.csv file created in Part 1 ,converting that into a Pandas DataFrame and analyzing it.
•	 Generating a map showcasing individual points representing each city within the city_data_df DataFrame.
. For each city, using the Geoapify API to find the first hotel located within 10,000 meters of the city coordinates.

This Challenge was a lot of fun to create. It was a lot of learning along the way as well, which was very informative. 

The visual outputs created on the maps were a thrill to observe. The fact that the Pandas dataframe datapoints can manifest on a worldmap in that manner is amazing to realize and seeing them manifest provides a satisfaction on the next level. Having the ability to hover over the points created and have them readout desired data through computation makes me feel empowered with new skills that I did not have. 

I am adding 2 screenshots of the map images created by my VacationPy code as I noticed that those displays did not upload as seen on my screen while commiting to this repo. I noticed that I was able to see the graphs created on the uploaded WeatherPy file and therefore not uploading them as well.

Thank you for the opportunity! 
