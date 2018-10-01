# Yahoo Weather widget for HABpanel (Openhab)

## Description
Yahoo Weather widget for HABpanel (Openhab).

## Download
**The widget and images**: [yahoo-weather.widget.json](https://github.com/BasvanH/habpanel-widget-weatherunderground)

**Yahoo Weather icons**: [weather-icons](https://github.com/erikflowers/weather-icons)

## Installation
- Install the [Weather](https://www.openhab.org/addons/bindings/weather1/) binding via PaperUI.
- Replace the Item list in /etc/openhab2/items: yourweather.items 
- Import the downloaded widget to your HABpanel.
- Download weather-icons repository from [here](https://github.com/erikflowers/weather-icons).
- The 'weather-underground-icons' folder should be stored in your '/etc/openhab2/html/' folder.
- Set the 'ServerPath' variable in the widget to '/static/weather-icons' (default).
- Place the three .png images in your '/conf/html/weather-icons/images' folder.

The complete structure would look like this:

- /conf/html
  - /weather-icons
    - /css
	  - weather-icons.min.css
    - /font
    - /svg <= this is where the different icon theme’s are stored
	- values
	- /images
	  - feel.png
      - humidity.png
      - wind.png
        

## Help
If you need any help, use this [topic](https://community.openhab.org/t/weather-underground-widget-with-forecast/40260) on the Openhab community forum.

For issues and feature requests, please use the [Issues module](https://github.com/BasvanH/habpanel-widget-weatherunderground/issues) on Github.
