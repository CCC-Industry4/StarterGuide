[Back to Main Menu](https://github.com/CCC-Industry4/IIOT-4.0-Project/tree/main)

# Building Smart Home

---

1. For instructions on building the Smart Home, see: [Keyestudio Smart Home Guide](https://docs.keyestudio.com/projects/KS5009/en/latest/docs/index.html)
2. For downloading libraries and sample codes, visit: [Keyestudio Smart Home Kit for ESP32](https://github.com/keyestudio/KS5009-Keyestudio-Smart-Home-Kit-for-ESP32)

3. Pin Connections:

- Temperature and humidity sensor to **IO17**
- Yellow LED module to **IO12**
- Steam sensor (used as touch sensor) to **IO34**
- Fan: **IN-** to **IO18**, **IN+** to **IO19**
- PIR motion sensor to **IO14**
- Left button module to **IO16**
- Right button module to **IO27**
- RFID module to **BUS I2C**
- LCD1602 display to **BUS I2C**
- 6812 RGB LED to **IO26**
- Gas sensor to **IO23**
- Buzzer sensor to **IO25**
- Servo controlling windows to **IO5**
- Servo controlling doors to **IO13**

4. The Arduino directory contains the required libraries and Arduino code for the home: [Arduino Code and Libraries](https://github.com/CCC-Industry4/IIOT-4.0-Project/tree/main/Arduino)

A. Arduino IDE Setup:

If the Arduino IDE is not installed and set up, follow these steps:

I. **Install the driver**  
II. **Add the ESP32 Environment**  
III. The libraries for this project require a previous version of the ESP32 environment.  
IV. Ensure **version 1.0.6** is installed by navigating to `Tools > Boards > Boards Manager`  
![Arduino IDE Board Manager](https://github.com/user-attachments/assets/fac6e1c6-107c-4fe6-b8f3-d1a12cbf5253)  
V. Select **ESP32 Dev Module** as the board: `Tools > Board > esp32 > ESP32 Dev Module`

B. Include all the libraries in the `libs` folder into the Arduino IDE.

C. Upload the **Arduino.ino** file to the Smart Home system.


---
