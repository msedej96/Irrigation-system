# Irrigation-system
Embedded irrigation system to provide a more optimal amount of water to the plants.

The device is capable to control of 8 electromagnetic valves (with the extension even more). It also has a sensor for measuring temperature and humidity in the air, as well as moisture in the soil. For off-grid irrigation systems, it can control the (submersible) pump and monitor the water level in the tank.

The valves (and pump) can be controlled according to a time schedule or according to the level of moisture in the soil. Manual control is also possible. Everything can be managed via the web interface. The local web server runs on the microcontroller itself. Over the air (OTA) updates of microcontroller firmware are possible thru Wifi network so there is no need to physically access device after installation. If there is no Wifi network it creates Wifi access point so you can connect with device directly.

The heart of the embedded system is an 32-bit ESP8266 MCU with a Wifi connection. Sensors and I/O pin expansions are connected via the I2C bus. The main PCB is custom made.

![MergedImages](https://github.com/msedej96/Irrigation-system/assets/103876373/d7d8fc12-655c-41ae-bd5d-75c89f1e9d03)
Here are some screenshots of web interface (Slovenian language).
