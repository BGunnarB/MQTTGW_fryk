# MQTTGW_fryk
The source code for the MQTTGW placed at Frykbacken
It is based on an Arduino UNO with an NRF24L01-PA radio
Connection is over Ethernet to the local router.

The GW interfaces with MySensors locally and is a client to the 
public CloudMQTT service at https://www.cloudmqtt.com

It also supports an BMP085 for indoor temperature and air pressure
and an Dallas DS18B20 for outdoor temperature.
