### Images from weather satellites
Satellites transmit signals that everyone can receive and decode. This is a documentation for building our own antenna to recieve and decode signals from three satellites - US NOAA 15,18,19.

**Components used:**
1. A long piece of wood. Ideally about 2-3 inches wide, 0.5-1 inch thick and 6-7 feet long
2. 2 shorter pieces of the same wood. Both pieces 21inches long.
3. 4 8-inch pieces of half inch dowel rod.
4. At least 10 feet of 50ohm coaxial cable.
5. Software defined radio (SDR)
6. Other common tools/materials

**Softwares/Programs used:**
1. SDRsharp software http://airspy.com/download/ (to control SDR)
2. Orbitron software http://www.stoff.pl/ (to track the satellite)
3. Audacity program http://www.audacityteam.org/download/ (to resample recorded audio)
4. WXtoIMG program http://www.wxtoimg.com/downloads/ (to decode resampled audio)

![Result](https://cdn.instructables.com/FT2/3FBR/J44FNQU9/FT23FBRJ44FNQU9.LARGE.jpg?auto=webp&frame=1&width=480&fit=bounds)

**Learning outcomes:**
* SDR(Software Defined Radio):
   * It's basically a radio communication sysetem where components like filtes, amplifiers, modulators, etc. are implemented by means of software/digital domain.
   * It consists of the receiver, the antenna and the computer running the software.
   * We can use it to listen to aircrafts, broadcasting stations, services and many more; and find daily life applications in mobiles and TVs.
* Basics of Antenna working:
   * In brief, em waves are produced upon oscillating charges of a dipole and it is received to an antenna which generally acts as a dipole.
   * The broadcasting station emits the waves to their satellites which then transmits it to our antenna aligned towards that direction.
   * There are many types of antennas like dipole and parabolic reflector.

![antenna](https://upload.wikimedia.org/wikipedia/commons/b/b2/Dipole_receiving_antenna_animation_4_616x380x150ms.gif)

**Full Story** with detailed structure can be found [here](https://www.instructables.com/id/Receiving-Images-From-Passing-Weather-Satellites-N/)
