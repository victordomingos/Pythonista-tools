## The NPK Weather App
A little utility to check the weather forecast for the next few days. This 
version is custom made for iPhone, so it uses Pythonista 3. It makes use of 
the web API provided by openweathermap.org and requires 'arrow' (which you can
install with pip using StaSh).

It shows the current weather and the forecast for the next 5 days.

![image](https://user-images.githubusercontent.com/18650184/28997435-ae49d7c0-7a0c-11e7-862a-018df2596137.png)

It can be customized for dark mode, by changing a simple variable (`DARKMODE`) in the first section of the code. By default it will show 3-hourly forecasts for the next 24h and then only for day time (no nightly weather forecasts for the remaining days). However, if you'd rather prefer to have full night and day weather forecast for all the next 5 days, you only need to set the `DETAILED` variable to `True`.

This version can use the device's location services, if available. If they are not available, the app falls back to a default location.
