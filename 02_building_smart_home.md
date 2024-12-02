[Back to Main Menu](https://github.com/CCC-Industry4/IIOT-4.0-Project/tree/main)
# Building Smart Home
---
1. For instructions on building Smart home see: https://docs.keyestudio.com/projects/KS5009/en/latest/docs/index.html
2. For downloading libraries and sample codes visit: https://github.com/keyestudio/KS5009-Keyestudio-Smart-Home-Kit-for-ESP32
3. Pins Connections

-Temperature and humidity to io17

-Yellow led module to io12 

-Steam sensor (used as touch sensor)  to the io34

-Fan (IN- to io18，IN+ to io19)

-PIR motion sensor to the io14

-Left button module to the io16

-Right button module to the io27 

-RFID module to the BUS I2C 

-LCD1602 display to the BUS I2C

-6812RGB LED to the io26

-Gas sensor to the io23

-Buzzer sensor to the io25

-Servo controlling windows to io5

-Servo controlling doors to the io13

4.The Arduino directory contains the required libraries and the arduino code for the home.
https://github.com/CCC-Industry4/IIOT-4.0-Project/tree/main/Arduino
A. Visit the Arduino Tutorial section if the Arduino IDE is not installed and set up.
I. Install driver
II. Add the ESP32 Environment
III. The libraries for this project are using a previous version of ESP32 environment.
IV. Ensure version 1.0.6 is installed. Click Tools > Boards > Boards Manager.
![Arduino IDE Board Manager](https://github.com/user-attachments/assets/fac6e1c6-107c-4fe6-b8f3-d1a12cbf5253)
V.Select ESP32 Dev Module as the board. Click Tools > Board > esp32 > ESP32 Dev Module. 
B. Include all the libraries in the libs folder to Arduino IDE.
C. Upload the Arduino.ino file to the smart home.

---
