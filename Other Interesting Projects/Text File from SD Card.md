### Text File from SD Card
This project uses a micro SD card to store a text file and print it out to a 16x2 liquid crystal display. It reads a .txt file with an Arduino Nano which can then display the contents of the text file on a liquid crystal display.

This project is really meant to be an example of how to use an SD card with Arduino.

**Components used:**
1. Arduino
2. LCD
3. Jumper wires
4. SD breakout board
5. MicroSD card
6. MicroSD to USB adapter
7. Potentiometer

**Code:**
~~~
#include <LiquidCrystal.h> 
#include <SPI.h> 
#include <SD.h>

File myFile;
const int rs = 2, en = 3, d4 = 7, d5 = 6, d6 = 5, d7 = 4; //lcd pins 
LiquidCrystal lcd(rs, en, d4, d5, d6, d7);

void setup() 
{ if (!SD.begin(10)) 
    { //make sure sd card was found while (true); }
lcd.begin(16, 1); 
lcd.setCursor(0, 0); 
lcd.print("myfile.txt"); 
delay(2000); 
lcd.clear(); 
}

void loop() 
{ myFile = SD.open("myfile.txt"); // open the file for reading

lcd.setCursor(16, 0); // lcd.autoscroll(); //enable auto-scrolling

if (myFile) 
{ while (myFile.available()) 
    { //execute while file is available char letter = myFile.read(); 
      //read next character from file lcd.print(letter); 
      //display character delay(300); }
myFile.close(); //close file
}
lcd.clear(); 
}
~~~
We simply make a circuit and upload the code to the arduino and it's done!!

**Learning Outcomes:**
* Programming LCD with an Arduino.
* SD card reading from arduino.
