### Automated Greenhouse
This project involves automatic greenhouse which allows features like soil humidity sensors, pump for watering, air temperature & luminosity sensing, automatic ventilation, time-lapse function, internet control, etc. Basically, it is collecting data coming from sensors then use some actuators to autonomously act on the plants environment.

**Components used:**
* [NodeMCUv3](https://lastminuteengineers.com/esp8266-nodemcu-arduino-tutorial/) (microcontroller)
* Arduino IDE
* [DHT-11](https://www.mouser.com/datasheet/2/758/DHT11-Technical-Data-Sheet-Translated-Version-1143054.pdf) (humidity & temperature sensor)
* [YL-38 & YL-69](https://medium.com/@chirag.parmar/know-your-sensor-yl38-soil-hygrometer-fceca860faac) (soil moisture sensor)
* [LM7805C](https://www.sparkfun.com/datasheets/Components/LM7805.pdf)
* LDR (light intensity sensor)
* Solid state relay modules 
* DC 12 V water pump
* Resistors, capacitors and other common materials/tools.

**Design:**
* Sesnors ensure the functiong of requirements like water pumps, lights, etc. For example, whenever soil moisture detected low by sensor, relay activates the water pump & activation of red/blue LEDs upon low light detection by LDR.
* Relay used for pump.
* It gets connected to an application already developed (Blynk app) to access the data directly on our phone
* Circuit built with NodeMCU microcontroller, sensors (like DHT-11), relays, pumps, LEDs and other mentioned componenets. 
* Rest is coding part. It is designed/downloaded and uploaded.

The **Full story** with the coding and detailed procedures/explanation : [Automatic Greenhouse](https://www.instructables.com/id/Upgradable-Automatedconnected-Indoor-Garden/)

**Additional comments:** This project serves as a good example of automation with cool interactions and technical setups. Further, reviewing it is made easy with Blynk which can be used for other automation projects as well. However, more applications/sensors can be added according to the needs of the plantation. 
