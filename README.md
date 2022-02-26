# Water Tandon

![alt text][Pic]

### **Description**

Water tandon project using AT89S51 Microcontroller written in Assembly Language. Sensors are used to indicate water level in the container through 2 red LEDs. White LED shows on water pump behaviour.

Conditions :

1. If the water reach sensor 1, LED 1 will be turned on
2. If the water reach sensor 2, LED 1 and 2 will be turned on
3. White LED indicate on what pump will do. Default value for LED will be turned on (act like pump will on and fill container with water). If sensor 1 and 2 already soak in, white LED will be turned off indicate that pump will be turned off. Then if water level below sensor 1 and 2, white LED will be turn on again indicate pump will be turning on.


### **How it works**

There are two sensors made of tin inside the cup which indicate different level of height and used for water level indicator. If tin solder soak in water, value of the resistance will be much higher than when it's dry. Resistance value will be picked up by OpAmp circuit and give high value (+5V) to the microcontroller to indicate water level in the container. Microcontroller give commands to turn on the LED which LED 1 indicate for water level on sensor 1 and LED 2 indicate for sensor 2.

[Pic]:https://github.com/adif-git/Water-Tandon/blob/master/WaterTandon.png
