# Smart_plant_contol_system_using_IOT

The goal of this project is to create a smart houseplant watering and monitoring system that analyses and records environmental factors to help plants thrive. The sensors collect and evaluate data regarding changing weather and soil moisture levels before sending timely warnings to the user’s Android phone.

 The sensors used here are DHT11 Temperature and Humidity Sensor, Capacitive soil moisture sensor v2.0 and a LDR sensor. The DHT11 sensor measures the environmental temperature and humidity levels. The moisture sensor senses the moisture content of the soil based on its capacitive content. The LDR sensor senses the sunlight intensity. We used ESP8266 Node MCU as a core component that processes all of these parameters and passed it on the cloud(BLYNK IOT). Based on these parameters the pump is turned on and off manually with respect to the critical conditions of the parameters. Automations are created on the IoT platforms that send warnings related to the 
environmental conditions.
