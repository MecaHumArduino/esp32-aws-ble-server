# ESP32 Coding Session 01 - Connect to WiFi and send data to AWS IoT

This coding session is the first video of a series where I will be exploring the ESP32 board following capabilities:

- Different WiFi modes
- Different Bluetooth abilities (Bluetooth Classic and BLE)
- Sending / Receiving data from AWS IoT

<img align="center" src="https://github.com/isbkch/esp32-aws-weather-station/blob/master/docs/esp32.png?raw=true" style="max-width:100%;" height="350">

→ ESP32 dev board I used in this video: https://amzn.to/3ifzLSY

# Description

In this video, I walk you through all the necessary steps to programme an ESP32 dev board to connect to WiFi, create a "Thing" on AWS IoT and secure it with a generated certificate, then use the certificate to connect the ESP32 board to the Thing. Then, we create a JSON document that we send to AWS IoT over an MQTT Topic every 2 seconds.

I'm using "Visual Studio Code" with "PlatformIO" plugin and standard Arduino libraries.

# Code Walk Through