# Lab 3: Visualizing International Space Station Information via APIs

**Create an R Markdown file for all of Lab 3.**

Make sure your final file is carefully formatted, so that each analysis is clear and concise.  Be sure your knitted .html file shows all your source code, including your function definitions. 

## The Open-Notify API

One of the Open-Notify APIs provides predictions of pass times for a given location when given the corresponding latitude, longitude, and altitude are given:

[Pass Times API](http://open-notify.org/Open-Notify-API/ISS-Pass-Times/)

### Pass Times for U.S. State Captials (100 points)

You can find the latitudes and longitudes for the U.S. state capitals at [this site](https://people.sc.fsu.edu/~jburkardt/datasets/states/states.html).

1. Use the Pass Times API to get the next 3 predicted pass times for all of the U.S. state capitals. Organize all of this information into a nice data frame (or data frame-like object) that will be easy to use for mapping.


### Mapping the Data (150 points)

1. Map the U.S. state capitals using `leaflet`

2. Find an image of your choosing to use as the marker icon, that's relevant for these data. (Do not reuse the astronaut helmet from last week)

3. The hover-over information for each marker should include the name of the state capital and the soonest predicted pass time. The click information should include the name of the state capital and all three predicted pass times. Make sure these times are in an easy-to-read format.


### Drawing the Route of the ISS (50 points)

Check out this video for [adding polylines](https://www.youtube.com/watch?v=iKESL0Iwmmw) to a `leaflet` map.

1. Overlay lines on your map that connect the U.S. state capitals in order of pass times (essentially east to west) so that we can see the expected pass order.


