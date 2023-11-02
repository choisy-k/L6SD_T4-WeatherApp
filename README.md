# L6SD_T4-WeatherApp
A simple weather forecast app, using .NET MAUI with CommunityToolkit.MVVM and OpenWeather API.

Please put your API key in Constants.cs file before proceeding.

Available feature as of 2/11/2023:
- Dynamic weather GIF (changes as the forecast changes)
- General data fetch based on city name search (temperature, wind speed, humidity, etc)

To be added:
- Get the current location's weather data when starting the app. Problem: Has not yet found related events to implement the code.
- CollectionView of the weather(s) throughout the day in a particular city. Problem: JSON is not properly deserialised, and keeps returning a null value.
- Adding DateTime into the UI...? Problem: Converting int variable Dt into readable date format.
