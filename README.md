# moe-temperature-sensor

Script for ESP8266 micro controller to read tamperature and humidity
sensor data from a DHT22 device. Sensor data is being transmitted
via MQTT in a connected WiFi network.

## Installation

## Configuration

The configuration of WiFi and MQTT login credentials is done via
```bash
defs.h
```

In that file, all relevant variables including SSID and password
for WiFi connectivity and user name and password for MQTT broker
login is configured.

When cloning the github repositoy you will find a ```defs.h.example```.
Please rename that to ```defs.h``` and edit the corresponding variables
to contain your respective credentials.
