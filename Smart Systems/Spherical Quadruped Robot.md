### Spherical Quadruped Robot
The present project describes a spherical quadruped robot. On standby mode, the robot looks like a sphere and transforms itself into quadruped to move. An ultrasonic sensor is used to avoid clash during motion.

**Components used:**
1. Arduino Nano
2. Servo Driver : Adafruit 16-Channel 12-bit PWM
3. Right Angle Male Header
4. Servomotor : MS-12016
5. NIMH battery pack : 4.8v - 1800 mAh
6. Ultrasonic sensor : SRF05
7. NeoPixel : Adafruit breadboard-friendly RGB Smart NeoPixel
8. Other common tools/materials

![model](https://content.instructables.com/FGW/73B2/K3E7SQ3Z/FGW73B2K3E7SQ3Z.LARGE.jpg?auto=webp&frame=1&width=1024&height=1024&fit=bounds)

**Short guide:**
* The Leg assembly with two servo motors each, bottom part assembly with a servomotor for door and the middle part assembly is combined with the head assembly (with one servo) which supports the ultrasonic sensor and its rotation.
* Removing head part gives access to the electronics, Arduino connections & battery recharging.
* Rest wirings are ensured and codes uploaded.

![Design](https://content.instructables.com/F8V/USA4/K5MGMMDI/F8VUSA4K5MGMMDI.LARGE.jpg?auto=webp&frame=1&width=1024&fit=bounds)

**Basic workings:**
* Ultrasonic sensor detects obstacles and head rotates rotates left/right accordingly to find free spaces.
* Servo driver board used to control the ten servos in the robot with I2C interface (two pins involved)

**Full Story** with more description can be found [here](https://www.instructables.com/id/Spherical-Quadruped-Arduino-Robot/)
