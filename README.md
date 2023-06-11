# Weather-App
Web weather forecast application based on location

This app takes in a location from a user and returns the weather in that location.
Features include:
- location correction (if any typos are in the name)
- informing if no weather data can be found
- detailed forecast of current time

This application makes use of the following APIs:
1. National Weather Service (NWS) API - used to forecast weather based on location
2. Maps.co Geocoding API - used to translate physical addresses into latitude and longitude coordinates
3. Google Places Autocomplete API - used to correct user entry to most likely location
4. AllOrigins CORS proxy server for Google API - used to satisfy Google API specifications

Background image credits:
"Weather at home" by denebola2025 is licensed under CC BY 2.0.
To view a copy of this license, visit https://creativecommons.org/licenses/by/2.0/?ref=openverse.
