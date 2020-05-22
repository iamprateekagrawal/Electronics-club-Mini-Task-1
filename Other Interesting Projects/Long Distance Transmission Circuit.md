### Long Distance Transmission Circuit
This project involves a basic Long Distance Transmission System circuit. It simply depends on straightforward transistors and a few resistors. A simple switch circuit for this has cons of expensive high gauge wires and the resisitive loss.

**Components used:**
1. LDR (Light Dependent Resistor)
2. Transistors.
3. Relay (as the switch)
4. Resistors, LED

**Short guide:**
* We order a PCB for the circuit. 
* All components are solderd to the PCB, with the LDR in-front of the LED without any obstructions and to show long distance, we use long coiled wires. 
That's it!!

![circuit](https://hackster.imgix.net/uploads/attachments/1104071/long_distance_transmission_schematics_AMNSbbiMv8.png?auto=compress%2Cformat&w=740&h=555&fit=max)

**Working**
* The LDR and the 2.2k resistor makes a voltage divider.
* When LDR doesnt receive light, its resistance will be infinite and no current will pass Q1 Transistor rather it flows from Vcc to Q2 Transistor's Base through 1k Resistor and activates it. The Load which is associated with the Q2 Transistor will be controlled up.
* When LDR Gets light, Q1 became conductive and every single current course through the briefest way that is VCC to GND 1k Resistor. No current will stream into the Q2 Transistor's Base and won't trigger the Q2 Transistor just as the Relay.

**Full Story** with greater explanation can be found [here](https://www.hackster.io/dhritimanhb2015/long-distance-transmission-system-circuit-3fb00c)
