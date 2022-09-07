# Air_Quality_Dashboard

See https://grilgamesh.github.io/Air_Quality_Dashboard/ to interact with the data.

This front-end dashboard builds on a join of two sets of data taken from reputable online sources: The NHS England asthma data is taken from gov.uk, and the air pollution data is taken from https://openweathermap.org.

## Technology used:
* html
* css
* flask
* d3
* javascript
* leaflet

## The Dashboard:
* a heatmap of the NHS asthma data
* a dropdown menu allowing users to choose an NHS centre to focus on
* a summary of the asthma rate for that centre, plus averages of the air quality measures, allowing these to be numerically compared
* a time series graph showing the six months of air quality data for the selected NHS centre, with the measures of air quality selectable. This can be further interacted with by visually cropping the data to a more limited time-frame
* a scatter plot of NHS centres (with the currently selected centre highlit), comparing asthma rate on the y axis with a selectable air pollutant on the x axis
* two violin plots, bolstering the scatter plot to illustrate a frequency curve of the x and y variables.

## Further additions:
In future I plan to add:
* regression lines and correlation measures to the scatter plot
* data for the rest of the UK
* location marker for the currently selected NHS centre on the heatmap
* a better tuned heatmap that works better at different zoom levels.


## Development history:
This is a cleaned-up repo of https://github.com/JovanS27/PROJECT_3 
