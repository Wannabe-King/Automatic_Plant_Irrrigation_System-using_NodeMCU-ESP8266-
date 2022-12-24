# Automatic_Plant_Irrrigation_System-using_NodeMCU-ESP8266-
Automatic Plant watering system using NodeMCU(ESP8266) and DHT11 sensor, pump, soil moisture sensor.
The project checks the moisture of the soil and if it goes below a specified level the motor starts automatically. In addition of automatic their is a manual mode as well where the motor can be turned on manually. Current soil moisture level , temperature and humidity of the surrounding. 

Setup:
1. Download Arduino IDE and all the libraries required for running the code.(DHT 11/22 libraries need to be given special care)
2. Make the circuit connections (Motor will be connected to 6th digital pin , DHT 11 to digital pin 4 and soil moisture sensor to 0th analog pin).
3. You can also a display in the circuit the code for it is present in commented from.
4. Setup Blynk IOT web dashborad and create a widgit for the same in Blynk IOT mobile app.(both must use same account to work)
5. Create Project Template in Blynk Iot web and create the required datastreams for the project.
6. Mobile App must look like **a79f0ffd-38aa-45a9-b13c-1327cf166e8b.jpg **
7. Change the credential for the Blynk app and wifi in the code .
8. All done .  
