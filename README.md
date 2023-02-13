# ESP8266_BME280_OLED
ESP8266 using BME 280 Sensor with OLED display


This is was writen program by Rui Santos.

The complete project details at https://RandomNerdTutorials.com/visualize-esp32-esp8266-sensor-readings-from-anywhere/

I added an OLED to display info every once in a while.

I added NTP client to read time.
adjustment needed here:

Google your UTC time difference, let's say it's  +3:30. Convert this to seceonds and then set your offset.

((3*60)*60)+(30*60)=12600 second is my offset based on 3:30 hrs.
  
  
