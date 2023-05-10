# Irrigation-system
Embedded irrigation system to provide a more optimal amount of water to the plants.

The device is capable to control of 8 electromagnetic valves (with the extension even more). It also has a sensor for measuring temperature and humidity in the air, as well as moisture in the soil. For off-grid irrigation systems, it can control the (submersible) pump and monitor the water level in the tank.

The valves (and pump) can be controlled according to a time schedule or according to the level of moisture in the soil. Manual control is also possible. Everything can be managed via the web interface. The local web server runs on the microcontroller itself. Over the air (OTA) updates of microcontroller firmware are possible thru Wifi network o there is no need to physically access device after installation.

The heart of the embedded system is an 32-bit ESP8266 MCU with a Wifi connection. 
