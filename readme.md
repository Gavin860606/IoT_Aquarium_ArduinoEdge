# Aquarium-Wemos_d1 

## Hardware requirements
 1. WeMos(LOLIN) D1 WiFi ESP8266
    
    <img src="https://github.com/Gavin860606/IoT_Aquarium_ArduinoEdge/assets/45595298/d24247a8-c767-47a4-8cee-fbf984828fe9" width="200" height="200">
 2. DS18B20 water temperature sensor
    
    <img src="https://github.com/Gavin860606/IoT_Aquarium_ArduinoEdge/assets/45595298/44fc62a6-d1ef-4ab7-a8ff-948186545741" width="200" height="200">
    
 3. PWM Fan 4-Pin * 2
    
    <img src="https://github.com/Gavin860606/IoT_Aquarium_ArduinoEdge/assets/45595298/e39cc71a-d848-4f14-97bd-a0744502aeb8" width="280" height="180">

## Diagram
 <img src="https://github.com/Gavin860606/IoT_Aquarium_ArduinoEdge/assets/45595298/7f85adde-d609-4f9f-a239-f3f8242abeec" width="1024" height="768">

## Arduino Libraries
 1. Azure SDK for C --> Handle Azure IoT Hub client Initial
 2. DallasTemperature --> Handle DS18B20 water temperature sensor
 3. ArduinoJson --> Handle MQTT response with JSON format
 4. ESP8266Wifi --> Handle Wifi connections
 5. PubSubClient --> Handle MQTT client and telemetry

## IoT_Configs
  Replace your wifi / Azure IoT Hub under the iot_cofnigs.h
