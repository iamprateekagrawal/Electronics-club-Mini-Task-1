### Solar Tracker
This prototype involves a dual-axis solar tracker controlled with Arduino Uno. It runs on two - automatic and manual modes.

**Components involved:**
1. four LDR sensors
2. two servomotors (SM1 and SM2)
3. potentiometer (for manual mode)
4. Arduino Uno
5. push-button

![system](https://hackster.imgix.net/uploads/attachments/1099367/fig1_06Dnc2AAKx.png?auto=compress%2Cformat&w=740&h=555&fit=max)

**Short guide:**
* 3D Mechanical design includes the panel, left-right & up-down servo motors, LDR sensors(inside dark tubes) on corners.
* Accodingly, the circuit and hardware designs are made and linked.
* The code to input values from LDR, to control SM and to run manual mode with potentiometer is uploaded. That's it!!

![Algorithm](https://hackster.imgix.net/uploads/attachments/1099371/fig4_vLrdhml8Yg.png?auto=compress%2Cformat&w=740&h=555&fit=max)

**Working:**
* In manual mode, potentiometer handles the panel and in automatic mode, light handles it. A push button switches between them.
* Average values from two right LDRs and two left LDRs are receiver, compared and panel rotated accordingly until the difference result is in the range [−10, 10]
* The LDR sensor circuitry is designed as a voltage divider circuit. The top of divider is 5 V, the ground is 0 V, and it's output is connected to an analog input of the microcontroller which converts it into a digital value between 0 and 1023. (ADC)
* all data is then sent through a USB cable to the computer and then present them in MS Excel. (PLX-DAQ Excel Macro is used)

![model](https://media.giphy.com/media/chP8Lh8cM5YkjufYPR/giphy.gif)

**Full story** with greater explanation along with codes can be found [here](https://www.hackster.io/336271/arduino-solar-tracker-41ef82)

**Additional comments:** This project displays good example of control theory and application along with designing algorithms.
