# WeatherGift-OpenWeather
New WeatherGift using OpenWeather. Created when Apple bough DarkSky in Spring 2020 and shut down the API for new users.

To use this project it is assumed you've set up the GooglePlace API and gotten an API key from both Google and OpenWeather.org. These should be in an APIKeys.swift file that is not part of this project. The structure of the file should be as shown below, but with your own API keys, where indicated.

Step by step videos for building your own version of this project can be found at the playlist at:
https://www.youtube.com/playlist?list=PL9VJ9OpT-IPR0QKk8tq1FVN5DaLcXO8FM

import Foundation

struct APIkeys {
    static let googlePlacesKey = "GOOGLE_PLACES_API_KEY_HERE"
    static let openWeatherKey = "OPEN_WEATHER_API_KEY_HERE"
}
