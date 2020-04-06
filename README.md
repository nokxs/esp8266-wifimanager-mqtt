# ESP8266: Combining WifiManager with MQTT

This example combines the MQTT [PubSubClient](https://github.com/knolleary/pubsubclient) library with [WifiManager](https://github.com/tzapu/WiFiManager). If you are just looking for the code, you can find it [here](src/main.cpp).

This enables
  - connecting to a Wifi over a HTML-Page
  - configuring the connection to the MQTT-Server over a HTML-Page
  - sending a message via MQTT
  - after everything is setup up correctly, the built in LED will blink

This project was build with [PlattformIO](https://platformio.org/) for an ESP8266-12f. It is based on the GitHub-Project [CurlyWurly-1/ESP8266-WIFIMANAGER-MQTT](https://github.com/CurlyWurly-1/ESP8266-WIFIMANAGER-MQTT), but uses [ArduinoJson](https://arduinojson.org/) Version 6.