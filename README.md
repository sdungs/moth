# MoTH
Monitoring Of Temperature and Humidity using Arduino. Including designs for Arduino shields, firmware and python readout scripts.

## MoTH-8
MoTH-8 is an Arduinio shield which is forseen to readout 8 NTCs/PTCs and 8 enviromental sensors. It also provides a connection for a LCD screen and WIFI module.

<img src="https://github.com/sdungs/moth/blob/master/moth-8_v1/design/moth8_v1_t.png" height="400" />

Sensor connection:

<img src="https://github.com/sdungs/moth/blob/master/moth-8_v1/NTC_connection.png" height="200" /> <img align="right" src="https://github.com/sdungs/moth/blob/master/moth-8_v1/ENV_connection.png" height="200" /> 

### BOM
- Board-To-Board Connector, 2.54mm, header (shield to Arduino connection)
- 2 contacts pin header (Molex): 22-27-2021
- 3 contacts pin header (Molex): 22-27-2031
- 4 contacts pin header (Molex): 22-27-2041
- SMD resistors foot print: 1206
- WIFI module: ESP8266 ESP-01
