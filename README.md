# 🔋 PCB_DESIGN_OF_BMS  
**Battery Management System (BMS) | Designed in Altium Designer**

This project presents a compact and efficient **Battery Management System (BMS)** designed using **Altium Designer**.  
It ensures safe charging, discharging, and protection of a **single-cell Li-ion (18650)** battery with monitoring, indicators, and protection circuitry.  
Optimized for reliable Li-ion battery performance and safety in embedded and power electronics applications.

---

## ⚙️ Key Features  
- **Charging Section (TP4056 IC)**
  - Constant current / constant voltage charging  
  - Built-in thermal regulation with NTC temperature sensing  
  - Simple resistor-based current programming (Rprog)
- **Battery Protection Circuit (DW01A + FS8205A MOSFET)**
  - Overcharge, overdischarge, and short-circuit protection  
  - Automatic cell cutoff for enhanced battery life
- **Indicator Section**
  - Red LED → Charging  
  - Green LED → Fully Charged / Standby
- **USB Charger Input**
  - Mini USB 5V input for convenient charging  
- **Protected Output**
  - Safe load connection with short-circuit and overdischarge protection  

---

## 🧮 RProg Calculation Example  

---

## 🧩 Circuit Overview  
### 1. Charging Circuit  
- Uses TP4056 for precise charging control  
- Includes charge and standby indication LEDs  
- Optional NTC thermistor (10K) for temperature protection  

### 2. Battery Protection Circuit  
- DW01A protection IC monitors cell voltage  
- FS8205A dual MOSFET handles switching and protection  
- Safeguards against overcurrent and reverse polarity  

### 3. Indicators  
- Dual LED display (Red/Green) for real-time status feedback  

### 4. USB Charger Input  
- Mini USB connector for 5V input  
- Filters provided via 10µF capacitor for stable operation  

### 5. Protected Output  
- 2-pin header output with built-in protection circuitry  

---

## 🛠️ Design Information  
- **Software Used:** Altium Designer  
- **Input Voltage:** 5V DC via USB  
- **Battery Type:** 3.7V Li-ion (18650 cell)  
- **Charging IC:** TP4056  
- **Protection IC:** DW01A  
- **Power MOSFET:** FS8205A Dual MOSFET  
- **LEDs:** Red (CHRG) & Green (STDBY)  
- **Thermistor:** 10K NTC (Optional for temperature monitoring)

---

## ⚡ Applications  
- IoT Devices  
- Embedded System Projects  
- Portable Power Modules  
- DIY Battery-Powered Electronics  
- Smart Battery Packs  

---

## 📂 Repository Structure  

---

## 📸 Circuit Preview  
The design includes the following sections:
- Charging Circuit with TP4056  
- Battery Protection using DW01A + FS8205A  
- Indicator LEDs for charge status  
- USB Input and Protected Output terminals  

![BMS Schematic](Images/BMS_Schematic.png)  
*(Replace with actual image path if available)*

---

## 🧠 Author  
**Designed by:** Harsh Saini  
**Tool Used:** Altium Designer  
**GitHub:** [github.com/harsh-hw-dev](https://github.com/harsh-hw-dev)

---

## 🪄 Keywords  
`BMS` `Battery Management System` `TP4056` `DW01A` `FS8205A`  
`Li-ion Charger` `PCB Design` `Altium Designer` `Electronics Project` `Power Management`

---

## 📜 License  
This project is open-source for educational and prototyping purposes.  
Please provide credit if reused or modified.

