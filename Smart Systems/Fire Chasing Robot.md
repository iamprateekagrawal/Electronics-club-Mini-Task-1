### Fire Chasing Robot
In this project, we see a firefighting robot that chases a flame and extinguishes it by blowing air at it from a fan.

**Components used:**
1. PICO
2. Flame Sensor
3. Small DC motor
4. Small Propeller
5. [L298N](https://www.alldatasheet.com/datasheet-pdf/pdf/22440/STMICROELECTRONICS/L298N.html) H-bridge motor driver
6. [PCA9685](https://cdn-shop.adafruit.com/datasheets/PCA9685.pdf) 12-bit 16-channel PWM driver
7. 2WD robot chassis kit
8. Other common materials/tools

**Short guide:** 
* We connect three flame sensors(for left, middle, right) to the PICO with their VCCs and GND to PICO's VCC and GND; D0 to PICO's digitals. Circuit is completed with DC motor, battery and transistor along with PCA9685 and L298N H-bridge module. 
* We start coding to know which flame sensor has a flame in front of (reading 0), and which doesn't(reading 1). 
* Accordingly we programme to rotate and move the robot with the flame detection and stop it when there isnt.

![Design](https://content.instructables.com/F0C/ZD75/K720C1EA/F0CZD75K720C1EA.LARGE.jpg?auto=webp&frame=1&width=1024&height=1024&fit=bounds)

**Learning outcomes:**
* PICO - Program In Chip Out(PICO) is world's smallest arduino compatible board with 9 I/O pins along with Vcc and Gnd pins. Can be used for small size projects and upload the codes accorfing to needs to it.
* L298N Motor Driver Module - high voltage Dual H-Bridge which are used to drive inductive loads that requires forward and reverse function with speed control such as DC Motors, and Stepper Motors.

**Full Story** with greater details and data can be found [here](https://www.instructables.com/id/Firefighting-Robot-Using-PICO/)

**Addiditonal comments:** The project can be modified to add pressured water ejection instead of fans, but the load here increases a lot, need powered motor to run the robot then.
