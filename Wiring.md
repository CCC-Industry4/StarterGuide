[Back to Main Menu](https://github.com/CCC-Industry4/IIOT-4.0-Project/tree/main)

[Back to Building Guide](https://github.com/CCC-Industry4/StarterGuide/blob/Alt-Guide/Building.md)

# Wiring Guide

## Table of Contents

- [Wiring Guide](#wiring-guide)
  - [Table of Contents](#table-of-contents)
  - [**Template I:**](#template-i)
  - [**Template K:**](#template-k)
  - [**Template H:**](#template-h)
  - [**Template J:**](#template-j)
  - [**Template F:**](#template-f)
  - [**Template M:**](#template-m)
  - [**Power Wiring:**](#power-wiring)


---

**Inventory:**
- 5 Short 3-pin connectors
- 4 Long 3-pin connectors
- 1 4-pin loose connector
- 2 4-pin connectors

The left image shows the 3-pin connectors, the middle image shows the 4-pin loose connector, and the right image shows the 4-pin connectors.

<p align="center">
  <img src="/images/wiring/Dupont.jpeg" width="30%;height: 250px; object-fit: cover;" />
  <img src="/images/wiring/Spread.jpeg" width="30%" />
  <img src="/images/wiring/Splicing.jpeg" width="30%" />
</p>



## **Template I:**

Find the following:
- 3 short 3-pin connectors
- 1 4-pin loose connector

Use a short 3-pin connectors. Temperature and Humidity Sensor: Pin IO17.

<p align="center">
  <img src="/images/wiring/Wiring%20I1.1.png" style=" width:48%;height: 250px; object-fit: cover;" />
  <img src="/images/wiring/Wiring%20I1.2.png" style=" width:48%;height: 250px; object-fit: cover;" />
</p>

Use a short 3-pin connector. Yellow LED Module: Pin IO12.

<p align="center">
  <img src="/images/wiring/Wiring%20I2.1.png" style=" width:48%;height: 250px; object-fit: cover;"/>
  <img src="/images/wiring/Wiring%20I2.2.png" style=" width:48%;height: 250px; object-fit: cover;" />
</p>

Use a short 3-pin connector. Steam Sensor: Pin IO33. Although it says Pin IO34 on the Keyestudio guide, the ESP32 does not support the Sensor on that IO. We are using the steam sensor as a touch sensor in our case.

<p align="center">
  <img src="/images/wiring/Wiring%20I3.1.png" style=" width:48%;height: 250px; object-fit: cover;" />
  <img src="/images/wiring/Wiring%20I3.2.png" style=" width:48%;height: 250px; object-fit: cover;" />
</p>


**REPLACE SECOND PICTURE WITH CORRECT WIRING**


Use a 4-pin loose connector. Fan IN- to IO18 S and IN+ to IO19 S, follow the other two wires according to the fan motor labelings and connect them into their respective V and G spots. Wire as shown:

<p align="center">
  <img src="/images/wiring/Wiring%20I4.1.jpeg" style=" width:48%;height: 250px; object-fit: cover;" />
  <img src="/images/wiring/Wiring%20I4.2.jpeg" style=" width:48%;height: 250px; object-fit: cover;" />
</p>


## **Template K:**

Find the following:
- 1 short 3-pin connector
- 2 long 3-pin connectors
- 2 4-pin connectors


Use a short 3-pin connector. PIR Motion Sensor: Pin IO14.

<p align="center">
  <img src="/images/wiring/Wiring%20K1.1.png" style=" width:48%;height: 250px; object-fit: cover;" />
  <img src="/images/wiring/Wiring%20K1.2.png" style=" width:48%;height: 250px; object-fit: cover;" />
</p>


Use a long 3-pin connector. Left Button Module: Pin IO16.

<p align="center">
  <img src="/images/wiring/Wiring%20K2.1.png" style=" width:48%;height: 250px; object-fit: cover;" />
  <img src="/images/wiring/Wiring%20K2.2.png" style=" width:48%;height: 250px; object-fit: cover;" />
</p>


Use a long 3-pin connector. Right Button Module: Pin IO27.

<p align="center">
  <img src="/images/wiring/Wiring%20K3.1.png" style=" width:48%;height: 250px; object-fit: cover;" />
  <img src="/images/wiring/Wiring%20K3.2.png" style=" width:48%;height: 250px; object-fit: cover;" />
</p>


Use a 4-pin connector. RFID Module: BUS 12C.

<p align="center">
  <img src="/images/wiring/Wiring%20K4.1.png" style=" width:48%;height: 250px; object-fit: cover;" />
  <img src="/images/wiring/Wiring%20K4.2.png" style=" width:48%;height: 250px; object-fit: cover;" />
</p>


Use a 4-pin connector. LCD1602 Display: BUS I2C.

<p align="center">
  <img src="/images/wiring/Wiring%20K5.1.png" style=" width:48%;height: 250px; object-fit: cover;" />
  <img src="/images/wiring/Wiring%20K5.2.png" style=" width:48%;height: 250px; object-fit: cover;" />
</p>


## **Template H:**

Find the following:
- 1 short 3-pin connector

Use a short 3-pin connector. 6812 RGB LED: Pin IO26.

<p align="center">
  <img src="/images/wiring/Wiring%20H1.1.png" style=" width:48%;height: 250px; object-fit: cover;" />
  <img src="/images/wiring/Wiring%20H1.2.png" style=" width:48%;height: 250px; object-fit: cover;" />
</p>


## **Template J:**

Find the following:
- 2 long 3-pin connectors

Use a long 3-pin connector. Gas Sensor: Pin IO23.

<p align="center">
  <img src="/images/wiring/Wiring%20J1.1.png" style=" width:48%;height: 250px; object-fit: cover;" />
  <img src="/images/wiring/Wiring%20J1.2.png" style=" width:48%;height: 250px; object-fit: cover;" />
</p>

Use a long 3-pin connector. Buzzer Sensor: Pin IO25.

<p align="center">
  <img src="/images/wiring/Wiring%20J2.1.png" style=" width:48%;height: 250px; object-fit: cover;" />
  <img src="/images/wiring/Wiring%20J2.2.png" style=" width:48%;height: 250px; object-fit: cover;" />
</p>


## **Template F:**

Wire the Window Servo wire. Wire to Pin IO5.

<p align="center">
  <img src="/images/wiring/Wiring%20F1.1.png" style=" width:48%;height: 250px; object-fit: cover;" />
  <img src="/images/wiring/Wiring%20F1.2.png" style=" width:48%;height: 250px; object-fit: cover;" />
</p>


## **Template M:**

Wire the Door Servo wire. Wire to Pin IO13.

<p align="center">
  <img src="/images/wiring/Wiring%20M1.1.png" style=" width:48%;height: 250px; object-fit: cover;" />
  <img src="/images/wiring/Wiring%20M1.2.png" style=" width:48%;height: 250px; object-fit: cover;" />
</p>


## **Power Wiring:**

Plug in the power from the battery holder to the ESP32.

![PowerWiring](/images/wiring/Power%20Wiring.png)


**Finished House:**

![FinishedWiring](/images/wiring/FinishedWiring.jpeg)


[Back to Building Guide](https://github.com/CCC-Industry4/StarterGuide/blob/Alt-Guide/Building.md)

---

