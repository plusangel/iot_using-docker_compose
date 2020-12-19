# IoT with docker compose

This the docker compose yaml file that will help you to setup the following servers:
- InfluxDB
- Telegraf
- MQTT-Mosquitto

The configuration file for the telegraf can be found in the telegraf.conf. This is the place that you can select the MQTT topics, the details of the database etc

To execute the script, you just need to type:
```
docker-compose -f iot.yml up
```