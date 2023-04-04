## How the sunshine hours varies in the year across continental United States

This is a project to provide a static visualization of the sunshine hours in the year by month across continental United States. We selected six representative cities: New York, Chicago, San Francisco, Miami and Seattle, roughly covering the edges of the continental United States. This project is created with Mapbox GL JS. Mapbox GL JS is a JavaScript library that uses WebGL to render interactive maps from vector tiles and Mapbox styles. This visualization is static, but we hope we can make it interactive in the future with Mapbox GL JS.

## Design of the visualization

We decided to use bar plot to visualize the sunshine hours of each city and we overlay these plots on the map of continental United States next to the city. The bar plot provides a straightfoward view of the sunshine hours and its change over the year. Overlaying the plot on the map can help audience quickly build a spatial sense of the information. We also leverage hue to imply the length of sunshine. The more red the bar is, the more sunshine in the month. In weather communication, people tend to associate red with sunshine and blue with percipitation. We also would like to introduce a website named [colorbrewer2.org](http://colorbrewer2.org/) to help people choose color schemes for their visualization.