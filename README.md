# esp-weather-station

This is a simple weather station for esp8266 devices and bmp180 pressure+temperature sensors. When run for the first time, it will await configuration via the serial connection, including wifi credentials, server address to dump to, and a unique identifier. 

On subsequent boots, it will attempt to connect to the wifi, then dump the temperature and pressure reading. If it can't connect to the wifi, it will provide a short window to enter setup mode.
