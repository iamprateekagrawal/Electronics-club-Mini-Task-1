### Wink Detector
This project involves a “wink-detector” which has two outputs, one for when you wink your left-eye and one for when you wink your right. Normal blinks, which involve both eyes, are ignored. This is basically to convert a Sparkfun AD8232 “Heart Monitor” to a “Wink Detector”.

**Components used:**
1. [AD8232](https://www.alldatasheet.com/view.jsp?Searchword=Ad8232%20datasheet&gclid=EAIaIQobChMI_ebt-OSm6QIVwmkqCh1TCwFsEAAYASAAEgK6pvD_BwE) ECG heart monitor module
2. Arduino Uno R3
3. [LM324](https://www.onsemi.cn/PowerSolutions/document/LM324-D.PDF) quad-op-amp
4. LEDs and resistors
5. other common tools/materials

**Design:**
* The output waveform from the AD8232 hovers about 1.5 volts DC
* When the left-eye winks the AD8232 output wave form rises towards 3.3 volts. When the waveform exceeds 2.8 volts the left-wink comparator output changes from zero to 5 volts.
* When the right-eye winks the AD8232 output wave form falls towards zero volts. When the waveform falls below 0.2 volts the right-wink comparator output changes from zero to 5 volts
* Normal blinks have no effect on the output as they are the equivalent of two simulataneous winks and it’s not possible for the AD8232 output to go in two opposite directions at the same time.
* There's a bit of circuit modification from how ECG is used as a heart monitor to how we use now. Instead of connecting to right and left arm along with right leg, we connect to right and left eyebrows along with the forehead.

**Full Story** with greater details and reasonings can be found [here](https://www.instructables.com/id/Wink-Detector/)

**Additonal comments:** We transform from one application of a device to another here. This project can be again extended to use for game interfaces/assistive technologies.
