### Swim Tracker
In this project, we make a swim tracker with data collections. The output is easily processed on Google maps where our water migration routes can be studied.

**Components used:**
1. BN-180 GPS Antenna Module
2. Adafruit Feather 32u4 Adalogger
3. Lipo battery
4. DS18B20 Waterproof Digital Temperature Temp Sensor Probe
5. Other common tools/materials

**Short guide:**
* Tracker was designed in Fusion 360 with constraints being waterproof, compact with access to SD card and Micro USB.
* We design and bulid the circuit with temp sensors and gps powered with a rechargeable battery.
* The program uses the TinyGPS++ library to interact with this chosen GPS unit. The loop function just asks for the data every set frequency.
* The unit is mounted to the back of your swimming goggles with temp probe hanging back and gps antenna pointed skywards.

**Learning outcomes:**
* BN-180 GPS Antenna Module can be used in GPS/GLONASS(GLObal NAvigation Satellite System) tracking
* Adafruit Feather 32u4 Adalogger is 'all-in-one' datalogger/reader with built in USB, microSD holder and battery charging.
* The project can be extended to determine other factors like speed, heading and time.

**Full Story** with more details can be found [here](https://www.instructables.com/id/Swim-Tracker/)
