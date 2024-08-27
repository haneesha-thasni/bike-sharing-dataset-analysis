# bike-sharing-dataset-analysis

A SHORT DESCRIPTION OF THE FEATURES.

* datetime - hourly date + timestamp

* season - 1 = spring, 2 = summer, 3 = fall, 4 = winter

* holiday - whether the day is considered a holiday

* workingday - whether the day is neither a weekend nor holiday

* weather -

1: Clear, Few clouds, Partly cloudy, Partly cloudy

2: Mist + Cloudy, Mist + Broken clouds, Mist + Few clouds, Mist

3: Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered clouds

4: Heavy Rain + Ice Pallets + Thunderstorm + Mist, Snow + Fog

* temp - temperature in Celsius

* atemp - "feels like" temperature in Celsius

* humidity - relative humidity

* windspeed - wind speed

* casual - number of non-registered user rentals initiated

* registered - number of registered user rentals initiated

* count - number of total rentals

Questions done :

1) Filtering for Summer Days (season = 2) and Clear Weather (weather = 1)
2) Filtering for Working Days with Temperatures between 10C and 20C
3) Filtering for Holidays with High Humidity (> 80%)
4) accessing all rows and columns from datetime to temp using loc
5) accessing first 50 rows and season only
6) Filtering for Winter Days with Temperature < 10°C and Casual Rentals < 10
7) Filtering for Summer Days with Humidity > 70% and Wind Speed < 10
8) Filtering for Winter Days (season = 4) with Low Wind Speed (< 10)
9) Filtering for Non-Working Days (workingday = 0) with Casual Rentals > 100
10) Filtering for Registered Rentals between 200 and 300 on Spring Days (season = 1)
11) Filtering for Clear Weather (weather = 1) and Temperature > 25°C
12) Filtering for Light Rain or Snow (weather = 3) on Holidays
13) Filtering for Working Days with Rentals Count > 500 and Humidity < 70%
14) Filtering for Summer Days with Light Wind (windspeed < 5) and High Rentals (> 700)
15) Filtering for Winter Days with Casual Rentals < 50 and Humidity > 85%
16) Filtering for Working Days with Temperatures < 10°C and Registered Rentals > 300
17) Filtering for Fall Days (season = 3) with Light Rain or Snow (weather = 3)
18) Filtering for Non-Working Days with Registered Rentals between 100 and 200
19) Filtering for Misty or Cloudy Weather (weather = 2) with Wind Speed > 15
20) Filtering for Spring Days (season = 1) with Registered Rentals > 400 and Humidity < 60%
