# Weather_analysis

## Part 1
The purpose of this particular analysis is to add weather descriptions to our vault of weather data from OpenWeather. Here, we generated 2000 random latitudes and longitudes, and via Python and the **citipy module**, we were able to find relevant weather data – including weather descriptions – on more than 700 towns and cities worldwide. We then stored this data into DataFrames to be exported into a csv file for our next procedure.

## Part 2
With our sample weather database reader, we then used Google API's to plot our towns and cities onto a map of tourist destinations. We made certain to add **try-except** blocks to account for any errors when using the pandas df.loc method. Additionally, we made use of HTML code to help mark each town/city with viable lodging on the map.
