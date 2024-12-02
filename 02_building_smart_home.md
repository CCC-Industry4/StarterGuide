[Back to Main Menu](https://github.com/CCC-Industry4/IIOT-4.0-Project/tree/main)

# Building a Smart Home

---

1. **Instructions for building the Smart Home:**
   - See the official [Keyestudio Smart Home Guide](https://docs.keyestudio.com/projects/KS5009/en/latest/docs/index.html).

2. **Downloading Libraries and Sample Code:**
   - Visit the [Keyestudio Smart Home Kit for ESP32 repository](https://github.com/keyestudio/KS5009-Keyestudio-Smart-Home-Kit-for-ESP32) to download necessary libraries and sample code.

3. **Pin Connections:**

   Connect the following components to the corresponding pins on your ESP32 board:

   - **Temperature and Humidity Sensor**: Pin **IO17**
   - **Yellow LED Module**: Pin **IO12**
   - **Steam Sensor (used as touch sensor)**: Pin **IO34**
   - **Fan**: **IN-** to **IO18**, **IN+** to **IO19**
   - **PIR Motion Sensor**: Pin **IO14**
   - **Left Button Module**: Pin **IO16**
   - **Right Button Module**: Pin **IO27**
   - **RFID Module**: **BUS I2C**
   - **LCD1602 Display**: **BUS I2C**
   - **6812 RGB LED**: Pin **IO26**
   - **Gas Sensor**: Pin **IO23**
   - **Buzzer Sensor**: Pin **IO25**
   - **Servo (Windows)**: Pin **IO5**
   - **Servo (Doors)**: Pin **IO13**

4. **Arduino Code and Libraries:**
   The Arduino directory contains the necessary libraries and code for setting up the Smart Home: [Arduino Code and Libraries](https://github.com/CCC-Industry4/IIOT-4.0-Project/tree/main/Arduino).

### A. **Arduino IDE Setup:**

If the Arduino IDE is not yet installed and set up, follow these steps:

   1. **Install the Driver**
   2. **Add the ESP32 Environment**
   3. The libraries for this project require an earlier version of the ESP32 environment.
   4. Ensure **version 1.0.6** is installed by navigating to `Tools > Boards > Boards Manager`.  
      ![Arduino IDE Board Manager](https://github.com/user-attachments/assets/fac6e1c6-107c-4fe6-b8f3-d1a12cbf5253)
   5. Select **ESP32 Dev Module** as the board: `Tools > Board > esp32 > ESP32 Dev Module`

### B. **Add Libraries to Arduino IDE:**

   - Include all the libraries from the `libs` folder into the Arduino IDE.

### C. **Upload the Arduino Code:**

   - Upload the `Arduino.ino` file to your Smart Home system.

---
