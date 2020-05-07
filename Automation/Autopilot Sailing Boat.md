### Autopilot Sailing Boat
This project involves autopilot configuration for sailing boats, especially for steering purposes.

**Components used:**
1. Arduino UNO (as MPU) + Arduino NANO (as WatchDog)
2. Beitian [BN-220T GPS](https://files.banggood.com/2016/11/BN-220%20GPS+Antenna%20datasheet.pdf)
3. Stepper Motor
4. Display LCD1602 2x16 characters + i2c converter circuit
5. [IC 24c04](https://www.alldatasheet.com/datasheet-pdf/pdf/23723/STMICROELECTRONICS/24C04.html) i2c eeprom
6. [IC 4051](https://www.alldatasheet.com/datasheet-pdf/pdf/173652/UTC/4051.html) multiplexer
7. [IC 7805](https://www.alldatasheet.com/view.jsp?Searchword=7805%20datasheet&gclid=EAIaIQobChMI1v_Qh82h6QIVi30rCh1HDAuxEAAYASAAEgLf5vD_BwE) voltage regulator + heat dissipator
8. Thermistor NTC MF52-103 10k
9. other common tools/materials.

**Design:**
* PCB produced according to circuit.
* Arduino UNO acts as the MPU and the independent external processor Arduino NANO acts as WatchDog.
* Beitian BN-220T is the GPS unit which sends(TX) out 2 times a second to arduino uno. The data contains all navigation data used to calculate correction to do by the Motor: date, time, position latitude and longitude, true course, speed and validity of satellites fix.
* EEPROM is used to read/write in this memory chip some parameters for Stepper Motor movements.
* Sensors connected to arduino via IC4051 multiplexer.
* Thermistor takes under control voltage regulator heating dissipator temperature.
* All circuit works at 5.0v supplied by LiPo 2S 7.4v 2600mA/h battery and IC 7805 voltage regulator.
* Buzzer and LED act as guide for emergency (low voltage/high temp) or process (autopilot/control) indication.
* The sketch uses around 65% of program and around 45% of memory.

**Full Story** with greater details and schematics can be found here: [Autopilot Sailing Boat](https://www.hackster.io/zoncatan/autopilot-for-sailing-boats-automatic-steering-system-b880bd)

**Additional Comments:**  Present model gives an overall outlook for an automation. The project can be extended to other parameter/research purposes like water depth/composition/temperature/velocity detection at different locations for any water body.
