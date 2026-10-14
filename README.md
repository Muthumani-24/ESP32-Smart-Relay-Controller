# ESP32 Smart Relay Controller PCB Design

An advanced, IoT-ready multi-channel smart relay controller powered by the **ESP32-WROOM-32** wireless module. Designed completely from scratch using **Altium Designer**, this board integrates stable low-dropout power regulation, precise temperature and sensor interfaces, audible/visual feedback, and robust switching outputs.

## 🚀 Project Overview
This hardware prototype successfully combines wireless IoT connectivity and local automation control onto a compact, optimized PCB layout:
1. **Processing & Connectivity Core:** Centered around the **ESP32-WROOM-32** module, providing integrated 2.4 GHz Wi-Fi and Bluetooth capabilities for cloud connectivity and remote monitoring.
2. **Power Regulation Stage:** Features an **AMS1117-3.3** Low Dropout (LDO) voltage regulator paired with input/output decoupling capacitors (`C1`, `C2`, `C5`, `C7`) to deliver a clean, stable 3.3V logic rail.
3. **Sensor Interface:** Integrates dedicated connection circuitry for precision digital sensors like the **DS18B20** temperature sensor alongside analog input channels.
4. **Feedback & Control:** Equipped with a piezoelectric buzzer (`LS1`) for audible alerts and transistor-driven NPN circuits (`Q1`) for safe inductive load and relay switching control.
5. **User Interface:** Includes tactile pushbuttons (`SW1`, `SW2`, `SW3`) for manual input, system reset, and bootloader mode configuration.

---

## 🛠️ Key Technical Specifications
* **Design Tool:** Altium Designer
* **Microcontroller Module:** ESP32-WROOM-32 (Wi-Fi & Bluetooth)
* **Voltage Regulator:** AMS1117-3.3 LDO Regulator
* **Sensor Support:** DS18B20 digital temperature sensor & analog inputs
* **Peripherals:** Piezo buzzer, indicator LEDs, tactile pushbuttons, and modular terminal blocks (`P1`–`P4`)

---

## 📷 PCB Visualizations & Renders

### 3D Board View
<img width="652" height="530" alt="3D_View" src="https://github.com/user-attachments/assets/113ef064-568f-424d-b2c0-78059cb3d833" />


### Top Layer View
<img width="627" height="545" alt="Top_View" src="https://github.com/user-attachments/assets/23726034-be9f-4bff-80f7-dcff18d46a48" />


### Bottom Layer View
<img width="603" height="545" alt="Bottom_View" src="https://github.com/user-attachments/assets/dba670c4-ecc8-41d4-8f53-eb54a7d28b71" />


---

## 📂 Repository Structure
```text
ESP32-Smart-Relay-Controller/
│
├── Documentation/            # Design renders, PCB file, and schematic PDF
│   ├── 3D_View.png
│   ├── Bottom_View.png
│   ├── PCB1                  # Altium PCB Document
│   ├── Schematic Pdf         # Schematic documentation
│   └── Top_View.png
│
├── Hardware/                 # Design files and manufacturing outputs
│   └── Outputs/
│       └── BOM.csv           # Bill of Materials
│
└── README.md                 # Project documentation
