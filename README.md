
# Weather

[![badge](https://img.shields.io/endpoint?url=https://gist.githubusercontent.com/JaouherK/a489177df4f24946281bdc1b21524b13/raw/79aacf61a7e32fe2e597f3f1980df1029d54894a/weatherMetaData.json)](https://github.com/JaouherK/streamDeck-weatherPlugin/releases/tag/v2.1.2)

`Weather` is a plugin that displays the weather condition as a picture image, the city name and the temperature of a given location. It is connected to multiple providers and needs an API Key to connect.

Possible providers:

- WeatherAPI
- OpenWeather

Optionally, you can choose the frequency of fetching updated data and the temperature unit ( Celsius or Fahrenheit).

# Button settings

The button is configured as follows:

- Title: Please do not set any value in order to display the temperature correctly
- Image: Please do not update picture in order to display the weather icon correctly
- Provider: the weather information provider: WeatherAPI or OpenWeather
- API key: your provider account key available in your account information on the associated provider website
- City Name: the city for which the information will be displayed on the button
- Laditude: the laditude of the location for weather lookup
- Longitude: the longitude of the location for weather lookup
- Temperature: the temperature unit ( Celsius or Fahrenheit)
- Fetch frequency: how often the data is updated (beware for free accounts the limits set by the provider)
- Display city name: Provides the possibility choose where to display the city name (also if we need to hide it)
- Round to nearest degree: Provides the possibility to show / hide digits after decimal point
- "Get my API key" button: to retrieve the key for your account
- "Report bug" button: to report a bug

# Features

- code written in Javascript
- cross-platform (macOS, Windows)
- Choice of Weather provider
- Choose temperature unit
- choose fetching frequency of the weather data
- Weather condition icon fit to display

![screen](screenshot.png)

# Installation

In the Release folder, you can find the file `com.jk.weather.streamDeckPlugin`. If you double-click this file on your machine, Stream Deck will install the plugin.

# Source code

The `Sources` folder contains the source code of the plugin.

Application main icon made by [Smashicons](https://www.flaticon.com/authors/smashicons) from [www.flaticon.com](https://www.flaticon.com/)
