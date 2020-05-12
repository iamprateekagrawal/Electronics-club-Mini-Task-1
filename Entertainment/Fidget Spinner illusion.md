### Fidget Spinner Illusion
In this project, we make a fidget spinner to use 'Persistence of Vision' effect which is an optical illusion whereby multiple discrete images blend into a single image in the human mind irrespective of its roatation velocity.

![Fidget Spinner](https://content.instructables.com/F00/IIHU/K8CD99PX/F00IIHUK8CD99PX.LARGE.jpg?auto=webp&fit=bounds)

**Components Used:**
1. [PIC 16F1619](https://www.alldatasheet.com/view.jsp?Searchword=Pic16f1619%20datasheet&gclid=EAIaIQobChMI_6y37ZKu6QIVFh4rCh2bjw8vEAAYASAAEgKiKvD_BwE) microcontroller
2. Hall sensor [DRV5033](https://www.alldatasheet.com/view.jsp?Searchword=Drv5033&gclid=EAIaIQobChMIi4HFgJOu6QIVhzUrCh1s-gstEAAYAiAAEgINevD_BwE)
3. magnets
4. [TLC59282](https://www.alldatasheet.com/view.jsp?Searchword=Tlc59282&gclid=EAIaIQobChMIg7-ykZOu6QIVmgsrCh2ieAROEAAYASAAEgIJbPD_BwE)
5. Step down converter [TPS62745](https://www.alldatasheet.com/view.jsp?Searchword=Tps62120&gclid=EAIaIQobChMI2_7CrJOu6QIVAn8rCh3G3A16EAAYASAAEgLDdvD_BwE)
6. [RN4871](https://www.alldatasheet.com/view.jsp?Searchword=Rn4871%20datasheet&gclid=EAIaIQobChMIzMqCvZOu6QIVVyUrCh0r0QYtEAAYASAAEgJjK_D_BwE) bluetooth module
7. Other common tools/materials

![Structure](https://content.instructables.com/FNG/HIRQ/K8CD99MM/FNGHIRQK8CD99MM.LARGE.jpg?auto=webp&frame=1&fit=bounds)

**Design:**
* Microchip PIC 16F1619 microcontroller used as its core.
* The MCU has built-in Angular Timer peripheral which uses omnipolar Hall sensor DRV5033 and one magnet to keep the track of current rotational angle.
* The diodes are driven by two 16 channel constant current shift register drivers TLC59282 connected in daisy chain.
* Step down converter TPS62745 converts 6V to a stable 3.3V.
* Bluetooth Low Energy module RN4871 (accessible by a PC) communicates with the microcontroller via UART interface.
* Bluetooth helps to change the displaying text and its color and to monitor battery level.
* We take the font generated in "The Dot Factory“ as input and transform it to suit the needs of this project, through an application developed in LabVIEW.

![Design](https://content.instructables.com/FWV/YT9V/K8CD99MY/FWVYT9VK8CD99MY.LARGE.jpg?auto=webp&fit=bounds)

**Full Story** with greater details and explanations can be found [here](https://www.instructables.com/id/Persistence-of-Vision-Fidget-Spinner/)

**Additional comments:** This model is a good example to learn about interactions between various devices and their setup combination. This similar structure can again be exploited for other mechanisms like communication and to implement complex operations.
