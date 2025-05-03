# 🔧 NebulaForge – 2.4GHz frequency jammer device

NEBULAFORGE is a 2.4GHz frequency jammer, capable of disrupting many types of signals such as:
+ Wi-Fi (can select jamming channel)
+ Bluetooth
+ BLE (Bluetooth Low Energy)
+ RC Drones
+ IoT devices & other wireless devices

## 📦 Required components

| No. | Component name | Quantity | Note |
|-----|-----------------------------------------|----------|----------|
| 1 | ESP32 NodeMCU | 1 | |
| 2 | TP4056 charging circuit (Micro USB / Type-C) | 1 | |
| 3 | JST PH 2.0 connector | 1 | |
| 4 | 3.7V Li-Ion battery | 1 | |
| 5 | SMA antenna | 2 | |
| 6 | E01-2G4M27D RF Module | 2 | |
| 7 | 10µF 50V Capacitor | 2 | |
| 8 | 5mm LED | 2 | |
| 9 | 220Ω Resistor | 2 | |
| 10 | SK12D07 Curved Pin Switch | 1 | |
| 11 | Sample PCB | 1 | Need to redesign from Gerber file |

⚠️ **Note:** The project does not provide detailed circuit diagrams for security purposes. Users need to research and build circuit diagrams themselves from Gerber data or from images.

## 🛠️ Assembly instructions

1. Prepare all components as shown in the table above.

2. Based on the Gerber file or principle image, place the components on the PCB in the correct position.

3. Solder the components firmly to the board.
4. Insert the Li-Ion battery into the TP4056 charging circuit via the JST port.

5. Connect the SMA Antenna and RF module to the ESP32 according to the schematic diagram.

> Note: The project requires users to have basic knowledge of electronics, reading circuit diagrams, and soldering skills.

## 🔌 Upload Firmware

Currently, firmware will be provided separately for each device. Flash support software will be announced later. You can follow the updates at:

- [Telegram Channel](https://t.me/czdeveloper_news)
- [Official Website](https://czdeveloper.gitbook.io/main/hardware/cyber-security/nebulaforge)

## 📚 Reference

- Official GitBook: [NebulaForge](https://czdeveloper.gitbook.io/main/hardware/cyber-security/nebulaforge)
- Setup Guide: [Detailed Guide](https://czdeveloper.gitbook.io/main/hardware/cyber-security/nebulaforge/huong-dan-thiet-lap)

---
