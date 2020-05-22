### Electric Skateboard
In this project, we see electric skateboard which can reach speeds of about 40km/hr(26mph) and run for about 18km.

**Components used:**
1. Longboard/Skateboard
2. Brush Less DC Motor
3. ESC (Electronic Speed Controller)
4. Drive Train (Pulley Belt/Chain Sprocket Version)
5. Motor Mount kit
6. 18650 cells
7. Lipo Cells

**Short guide:**
* We design the pulley belt, motor mount and setup the battery and motors. 
* Motor was mounted to the rear right wheel(after removing it) and wheel connected to it with a pulley. 
* ESC connected to the motor, battery pack and to radio receiver. 
* We can build our own radio controller with the help of Arduino and nRF24L01 Module
That's it!!

**Learning outcomes:**
* Wireless arduino with nRF24L01 Module:
   * SPI interface used between them to send data packages.
   * For connections, me connect Vcc, Gnd, CSN, MOSI, MISO, SCK, CE pins of each other.
   * For the code, we define packages, pipe address and channel, data rate for range and make data structure in the loop()
* ESC(Electronic Speed Controller)
   * It’s the link between your batteries and the motor.
   * It also connects to receiver that goes to remote control. The ESC gets the 'commands'(PWM Signal) from the receiver that (Duty Cycle) tells it how much the remote's throttle is pushed.
   * It then controls the amount of energy that passes from the battery to the motor, hence controlling the motor's speed.

**Full Story** with greater details can be found [here](https://www.instructables.com/id/DIY-Electric-Longboard-1/)
