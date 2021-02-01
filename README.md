# World_Weather_Analysis

## Overview

This analysis helps to look out at different weather patterns around the globe and gives an insight to travellers around the world who wish to plan vacation trips.
The breakdown of this anlysis is as follows:
1. Weather Database
2. Vacation Search
3. Vacation Itinerary

### Weather Database

The Open Weather Map API helps to pull the following information of 749 different cities:
1. Maximum Temperature
2. Cloudiness
3. Wind Spped
4. Humidity
5. Current Weather Description
The above information along with the latitudes and longitude information helps the travellers to find out the weather of their destination cities.

### Vacation Search

This search uses the weather database information and uses Google Maps API to plot different travel destinations along with locating hotels/lodging.
The image below shows the locations of all the places in the database that have a temperature range of 70 to 90 degrees Farheneit.



### Vacation Itinerary

This search takes the information from Vacation search and uses Google Maps Direction API to create a vacation itinerary. For example the image below shows a four stop itinerary in Asia that features Veraval, Tezu, Pathein and Machilipatnam.


It also shows hotels at each destination.
