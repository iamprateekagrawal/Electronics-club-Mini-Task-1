### Slow-Scan TeleVision(SSTV)
In this project, the capsule basically sends images SSTV using analog form through the radio which can also help to provide data such as temperature or altitude from images.

**Components used:**
1. The brain Pi-Zero
2. [Rtc DS3231](https://components101.com/modules/ds3231-rtc-module-pinout-circuit-datasheet): High precision clock
3. [BMP180](https://components101.com/sensors/bmp180-atmospheric-pressure-sensor): Sensor temp and barometric pressure sensor
4. Radio module
5. 600 OHM AUDIO TRANSFORMER
6. antenna
7. [DRA818V](https://datasheetspdf.com/datasheet/DRA818V.html): Radio Module
8. Other common tools/materials

**Design:**
* Raspbian installed with graphical environment, accessing the menu raspi-config will enable the camera interface, I2C and Serial.
* RTC and BMP180 mounted together, raspi-cam v2 camera module used.
* Created a simple circuit that generates the audio through two PWM GPIO ports.
* DRA818V (wireless voice transciever VHF) module used. The communication with the module is through serial port.
* Turnstile antenna(crossed dipole) used for a good coverage(30km) for the capsule.
* Powered with 6 pack of AA lithium battery and step-down. 
That's it!!

![Circuit](https://cdn.instructables.com/FWJ/J944/JGGTSMSE/FWJJ944JGGTSMSE.LARGE.jpg?auto=webp&frame=1&width=849&height=1024&fit=bounds)

**Full Story** with more details can be found [here](https://www.instructables.com/id/SSTV-CAPSULE-FOR-HIGH-ALTITUDE-BALLOONS/)

**Additional Comments:** This project serves a good example for transmission modules with the help of Raspberry pi and other important components like transceiver, antenna, RTC, etc.
