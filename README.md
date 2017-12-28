# RaspberryTouch-Radio
A Raspberry Pi Webradio compatible with WaveShare TouchScreen

Main Points
-used Display WaveShare Spotpear
-Radioplayer MPC/MPD
-Librarys
  -PyGame (Display elements)
  -pyowm (weather data)
  -Requests (HTML Requests)
-Websites
  -https://openweathermap.org (Weather data)
  -https://sunrise-sunset.org/ (Sunrise data)


Installation:

For this project you only need a TouchScreen or a display with a button for your Raspberry Pi.
The best concept is to use a TouchScreen with a Button for better use comfort.

-install Raspbian Jessie
-install Display Driver
  -https://www.waveshare.com/wiki/3.5inch_RPi_LCD_(A)
-get librarys
  -sudo pip install pyowm
  -sudo pip install requests
-get the software
  -sudo git RaspberryTouch-Radio
-start with sudo python RaspberryTouch-Radio.py
