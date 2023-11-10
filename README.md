# python-api-challenge
In this challenge, we generated a dataframe of cities by creating random sets of coordinates and finding the closest city to each set.
We then found weather data for each city in the list, grouping them in clusters of 50 for ease of tracking.
We outputted this data to a csv.
Once we had done this we created scatterplots of various weather markers vs city latitude.
We then separated the data into hemispheres to set us up to run linear regressions.
I created a loop to store all of my regression values in a dictionary, then plotted eacch linear regression & accompanying equation.
We wrote a summary of each regression's results.
In part 2 we imported our outputted csv and plotted the cities on a map, scaled to their relative humidity.
We then decided our ideal weather criteria and narrowed the list down to ~10 cities within those ranges.
We used GeoApify API to find the closest hotel to each one of these cities, and added those results to the dataframe.
We then plotted our ideal weather cities on a world map.

This assignment didn't require many resources--most of what I needed was provided in in-class examples or pre-loaded code.
I asked ChatGPT how to convert Unix date format to standard in Python.
It also helped me debug my weather regression loop, but a lot of that was pulled from the restaurant search in-class example, and the final debugging steps were my own common sense.
