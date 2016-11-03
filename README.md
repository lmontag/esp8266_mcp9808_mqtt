# esp8266_mcp9808_mqtt

This is an Arduino's Sketch which allow to ESP8266 module to read temperature from MCP9808 sensor 
and publish the data through MQTT protocol to a server via WiFi.

## Components:

- **ESP8266**
- [MCP9808 Adafruit temperature sensor](https://www.adafruit.com/product/1782)
- [MCP9808 library](https://github.com/adafruit/Adafruit_MCP9808_Library/archive/master.zip)
- [PubSubClient Library](https://github.com/knolleary/pubsubclient)

## Load Sketch from Arduino IDE:

- Install Arduino IDE 1.6.8 from the Arduino website.
- Start Arduino and open "Preferences" window
- Enter http://arduino.esp8266.com/stable/package_esp8266com_index.json into "Additional Board Manager URLs" field
- Open "Boards Manager" from "Tools" > "Board menu" and install "esp8266" platform
- Select your ESP8266 board from Tools > Board menu after installation
