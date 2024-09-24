# weather-api-viz
Visualizations of weather data using the OpenWeather API and a city-finding library in Python. This was a simple exercise but I was proud of the output since I needed to marry datasets that had been made with very different assumptions/expectations (the definition of "city" is not as universal as you might think) and think about the data in practical way. Acquiring 500 unique cities' worth of data took a fair amount of time even after I had optimized the code not to send HTTP requests for duplicate cities.

Visualizations can be found in `/output` and more detailled write-ups are available within the Visualizations section of the `WeatherAPI.ipynb` file (either `ctrl+F` for it or just scroll to the bottom). The `VacationAPI.ipynb` file contains an additional challenge which may be developed further if I return to the project.

If you want to run this program locally, you can either use the provided CSV file (and modify `WeatherAPI.ipynb` accordingly) or create an account on [OpenWeather](https://openweathermap.org) and provide your own API key in a `.py` file named `api_keys.py`.
