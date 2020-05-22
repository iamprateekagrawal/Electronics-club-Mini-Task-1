### Gesture Controlled Maze
In this project, we control a labyrinth maze with gestures. Maze is controlled via wearable band or Bluetooth app developed using MIT App Inventor. The gyroscope sensor data from the band is transmitted through WiFi connection to the Wemos D1 Mini device (esp8266) which controls the servos that tilt the maze. The data transmission is through UDP protocol.

**Components used:**
1. Wemos d1 mini
2. SG90s Servo Motor
3. [ESP01](http://www.microchip.ua/wireless/esp01.pdf)
4. [MPU6050](https://components101.com/sensors/mpu6050-module)
5. [TP4056](http://www.tp4056.com/d/tp4056.pdf) LiPo Charger Module
6. 3.7v 400mAh LiPo Battery
7. Fitbit band or watch strap
8. 25mm Neodymium magnets
9. Other common tools/materials

**Short guide:**
* We 3D print the maze part and attack servos to it with its respective wires soldered to Wemos board. Magnet is glued and covered. 
* Maze is done and codes uploaded to Wemos using Arduino IDE. 
* The wearable band has programmed ESP01, MPU6050 sensor, 3.7V 400mAh LiPo battery, mini slide switch, TP4056 LiPo Charger Module.

**Working:**
* The maze is working in Access Point (AP) mode and the band is working in Station Mode.
* Band tries and connects with maze, then ESP01 communitcated with MPU6050 with I2C protocol.
* Sensor is oriented first and then roll & pitch angle from MPU6050 is calculated.
* It calculates angle every 4ms and then it transmits these angle values to the maze which makes the servo motors on the maze to rotate.
That's it!!

**Full Story** with more description and details can be found [here](https://www.instructables.com/id/Gesture-Controlled-Maze/)
