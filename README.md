# python-api-challenge

The purpose of this program is to first look at correlations in location along the latitude for different weather metrics.
It then uses VacationPy to look for locations that exist within your ideal weather conditions and then subsequently find hotels within the region. 

If I were to actually use this program in real life I would have added a language feature to ensure that you could speak the language and then likely make a list of approved country codes for areas that are deemed "safe".
The current program recommended locations in Russia and I would not consider that safe for US citizens at the moment.

To successfully use this program it will require geoapify and openweathermap API Keys. The file call is from an api_keys.py - place this file in both the WeatherPy and VacationPy folders for the keys to be accessed. 
# OpenWeatherMap API Key
weather_api_key = "YOUR KEY HERE"

# Geoapify API Key
geoapify_key = "YOUR KEY HERE"

Co-Pilot was installed in VS Code - OK'd by both the instructor and the SSM.
ChatGPT 4 was used to assist in generating the plot density analysis for finding empty space on the different scatter plots. It took several iterations and a lot of guidance on my part correcting math etc.
The annotation coordinates were not a primary point of grading and just an extra flair.
Otherwise everything I generated myself.

The file came with some markdown reqeusts - although they were not part of grading. While I completed them, I instead used the linear regression function I created to predetermine the possible variations in 
pearsons coefficient and the r squared value to assist in determining any relevance for the scatter plot.
