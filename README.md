#NOAAAV-WxWg-Setup
##NOAA Aviation Weather Widget

This is a project I have been working on for Android that allows one to enter a list of ICAO airport identifiers and have the hourly METARs for those airports scraped from the National Oceanic and Atmospheric Administration's website. These METARs will then be displayed in raw form as a widget.

A METAR, defined by the FAA in the Aeronautical Information Manual as an *aviation routine weather report* (often defined referenced internationally as the Meteorological Terminal Aviation Routine Weather Report or Meteorological Aerodrome Report), is the most common format in the world for the transmission of current weather observations, and is standardarized through the International Civil Aviation Organization (ICAO). A METAR includes a wide range of information about current weather conditions, including (among other things) time and place of observation, wind direction and speed, temperature, dew point, cloud cover and heights, visibility, barometric pressure, runway conditions, and types of precipitation. Because of this once one becomes familiar with the raw format of it, it becomes a very quick and efficient way to see weather conditions at a particular observation site.      

Here is an example METAR:
**KRNT 271553Z 07004KT 8SM -RA FEW006 OVC038 08/07 A2973 RMK AO2 RAE23B47 SLP073 P0002 T00830000 $**

There are many great resources on the internet for learning how to decode the various elements in a METAR.

Though it shouldn't need to be said, this application should not in any way be used as a substitute for a pre-flight weather briefing. This application is only meant to provide an easy way to see the most recent observational weather data.

##Possible future additions:
* Validation of Airport identifier/METAR
* Addition of TAFs for weather forecasting visibility
* Add support for using AviationWeather.gov's 'ADDS Text Data Server", which would allow easy parsing of individual elements.
* Ability to select which elements of the METAR to display 
