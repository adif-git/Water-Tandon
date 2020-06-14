# Water Tandon

![alt text][Pic]

## Description
This is my water tandon project using AT89S51 Microcontroller in Assembly Language. Sensors are used to indicate water level in the container and water level will be showed using 2 red LED. White LED shows on water pump behaviour.

Conditions : 
- If the water reach sensor 1, LED 1 will be turned on
- If the water reach sensor 2, LED 1 and 2 will be turned on
- White LED indicate on what pump will do. Default value for LED will be turned on (act like pump will on and fill container with water). If sensor 1 and 2 already soak in, white LED will be turned off indicate that pump will be turned off. Then if water level below sensor 1 and 2, white LED will be turn on again indicate pump will be turning on. 


## How it works
From this picture, notice there are two sensors inside the cup with different level of height. Sensors are made from tin solder. Thi s sensors will be indicator for water level. If tin solder soak in water, value of the resistance will be much higher. Then this value will be picked up by Op-Amp circuit and give high value (+5V) to the microcontroller to indicate that water already soak the sensor. Microcontroller then turn on the LED on which level the sensor already soaked in. LED 1 indicate for sensor 1 and LED 2 indicate for sensor 2.

Note : Sorry for low quality video because this is an old project. There is some part when container is full, I need to fix jumper cable because cable was loose. Thank you

[Pic]:https://github.com/adif-git/Water-Tandon/blob/master/WaterTandon.png
