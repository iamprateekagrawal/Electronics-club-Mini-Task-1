### Alarm Bike Lock
Brief Description: In this project, we see a simple shock activated alarm lock. It include interesting components like piezoelectric discs, amplifiers and a logic circuit as well.

**Components used:**
1. LiPo Battery
2. [TP4056](http://www.tp4056.com/d/tp4056.pdf) board
3. [LP2950](http://www.ti.com/lit/ds/snvs764q/snvs764q.pdf?&ts=1590159047380) 3.3V Regulator
4. 3.3V Buzzer
5. MCP602 OpAmp
6. 200k Trimmer
7. CD4013 Flip Flop
8. IRLML6344 MOSFET
9. Piezoelectric disc

**Short guide:**
* We build the circuit according to the diagram 
* 3D printing for housing and mounting the components to it. 
* We make it to the bicycle.
That's it!!

![Circuit](https://content.instructables.com/FRF/JSVS/K891P8RL/FRFJSVSK891P8RL.LARGE.jpg?auto=webp&frame=1&width=784&height=1024&fit=bounds)

**Learning Outcomes:**
* Piezoelectric disc:
    * creates voltage when hit (shock)
    * voltage is low, so in this project we amplify it (34 times) with a MCP602 OpAmp
* TP4056 board:
    * Attached to the LiPo battery for its protection.
    * Protects it from overcurrent, overdischarge & overcharge.
* LiPo battery here gives around 3.5-4.2V voltage and hence we use 3.3V buzzer/circuit points.
* LP2950 voltage regulator helps obtain fixed voltage (as required of 3.3,5 or 3V)
* 200k Trimmer is a potentiometer to trim the value of a resistor.

**Full Story** with greater description can be found [here](https://www.instructables.com/id/DIY-Alarm-Bike-Lock-Shock-Activated/)
