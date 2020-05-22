### Contactless Voltage Detector
This project is to make a simple contactless AC voltage tester. The circuit for this tester can be made using different configurations like IC4017 or with IC555 or even with transistors.

**Components used:**
1. [IC 4017](https://www.electroschematics.com/wp-content/uploads/2011/04/4017-ic-datasheet.pdf) decade counter or [IC 555](https://datasheetspdf.com/datasheet/IC555.html) .
2. 555 timer IC
3. 2N2222 General Purpose NPN Transistor
4. simple antenna
5. Other common tools/materials

![Design](https://cdn.instructables.com/F3N/EJWD/JT4TP59T/F3NEJWDJT4TP59T.LARGE.jpg?auto=webp&frame=1&width=1024&fit=bounds)

**Working of tester based on IC555:**
* When the voltage on Pin-2 falls below 1⁄3 of VCC the Output on Pin-3 goes HIGH and the LED lights up.
* As long as this pin continues to be kept at a low voltage, the OUT pin will remain HIGH.
* So, when the antenna detects an alternating input the output goes HIGH and LOW and the LED flashes accordingly.

![Design](https://cdn.instructables.com/FK7/ZJ13/JT4TP5WR/FK7ZJ13JT4TP5WR.LARGE.jpg?auto=webp&frame=1&width=1024&fit=bounds)

**Working of tester based on transistors:**
* When we move the antenna close to an AC energized object, a small current gets induced into the antenna due to the electromagnetic induction.
* This current triggers the first transistor and output of the first transistor triggers the second and third.
* The third transistor then turns ON the LED and buzzer circuit, indicating the presence of AC voltage.

![Design](https://cdn.instructables.com/FY2/WK5X/JT4TP5AP/FY2WK5XJT4TP5AP.LARGE.jpg?auto=webp&frame=1&width=1024&fit=bounds)

**Learning Outcomes:**
* IC4017:
   * 16 pin decade(0 to 10) counter and sequentially counts in a pre-defined time and reset the count or hold it as required.
   * can be used for low range counting application.
* IC555:
   * 8-pin IC which can be used in a timers, pulse generations, oscillator applications.
   * Basically has three 5k ohm resistors in series(so the name) between 8th and 1st pin, acting as voltage divider.

**Full Story** with more details and data can be found [here](https://www.instructables.com/id/Contactless-Voltage-Detector/)
