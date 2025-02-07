# 🛠 BeanCounter – SMT Parts Counting Tool (Forked)

This is a **fork of the original BeanCounter project** by Nick Poole. The **BeanCounter** is a compact SMT parts counting tool designed to accurately track electronic components in carrier tapes. It is powered by an **ATtiny861V-10MU microcontroller** and features an **IR sensor-based counting system** with a **7-segment display**.

---

## 🚀 Features
✅ Counts SMT parts in carrier tapes efficiently  
✅ Supports **Inventory Mode** (fast, no direction tracking) and **Dispense Mode** (precise, directional counting)  
✅ **7-segment LED display** for real-time count tracking  
✅ **EEPROM storage** for user settings (tape pitch, mode selection)  
✅ **Self-test function** for IR sensor diagnostics  
✅ Optimized firmware written in **Arduino (C++)** using **Spence Konde's ATTinyCore**  

---

## 🔧 Enhancements in This Fork
🚀 Improved firmware with optimized **state management**  
🚀 Fixed pin definitions and **hardware configurations**  
🚀 Enhanced **timer settings and IR sensor handling**  
🚀 Refined **power efficiency and EEPROM usage**  

---

## 📂 Getting Started
### 🖥️ Clone the Repository
```sh
git clone https://github.com/YourGitHubUsername/BeanCounter.git
cd BeanCounter
```

## Flash the ATtiny861 Using AVRDude
```sh   
avrdude -c usbasp -p t861 -U flash:w:BeanCounter_V10.ino.hex:i
```

## 🛠️ Modify and Customize

Open the project in Arduino IDE
Install Spence Konde's ATTinyCore for ATtiny861V-10MU
Adjust settings (tape pitch, counting mode, etc.) in EEPROM


