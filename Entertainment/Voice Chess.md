### Voice Chess
In this project, we need to make a voice commanded chess board which would especially help those with disabilities. It shall accept voice commands and process it to produce required movement of chess pieces on the board.

**Components Used:** 
1. Android phone
2. L298N Driver modules
3. Arduino Mega
4. Bluetooth module for arduino 
5. Relay switch
6. 2 Stepper motors
7. Batteries 
8. 32 metal (it must be magnetic, ex: iron) washers
9. Other common tools/materials.

**Design:**
* Android app converts voice to texts and sends this string to the arduino via bluetooth module serial communication on 2.4 Ghz band.
* The code (according to pre-set number system) handles on occupied houses and moves the pieces accordingly - to instructed house with stepper motor and/or falls the piece there to a box with motors. 
* Electromagnetism used to move pieces and it's activated through relay.
* Pieces move between the houses without knocking others and sticks to their position on board with the help of electromagnets.
* Motors then move back and relay & LED is turned off to wait for further commands.
* Rest involves calculations for the setup.

**Short guide:** We choose wood of appropriate dimension and then install x-axix and y-axis motors with pulleys and belts attached to it. We prepare the batteries and connected the magnet and the electromagnet. Simply connect according to the circuits and programme the codes. Now, stowage the components.

![Demo](https://media.giphy.com/media/lQCFDWxOD3TOshxrTk/giphy.gif)

**Additional Comments:** Both mechanical+electrical works required to build it - the motors, magnets and the pulley-belt system all work simultaneously. Alongside, mathematical algorithms were defined to build up a working programme code model. Efficieny of the model can be increased by having 'confirm' option for user-instruction and producing detailed game results with skill rating of each player at the end which shall require more components and coding applications.
