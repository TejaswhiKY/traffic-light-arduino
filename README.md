# 🚦 Arduino Traffic Light System

This project simulates a traffic light using an Arduino UNO and three LEDs: Red, Yellow, and Green.  
Each LED turns ON for a specific amount of time to represent a real traffic signal.


## ⏱ Timing Sequence
| Light  | Duration |
|--------|----------|
| 🔴 Red | 30 seconds |
| 🟢 Green | 15 seconds |
| 🟡 Yellow | 5 seconds |

The cycle repeats continuously.

## 🔧 Hardware Required
- Arduino UNO  
- Breadboard  
- Red LED  
- Yellow LED  
- Green LED  
- 3 × 220Ω resistors  
- Jumper wires  


## 🔌 Pin Connections

| LED     | Arduino Pin | Resistor | Ground |
|---------|-------------|----------|--------|
| Red     | D2          | 220Ω     | GND    |
| Yellow  | D3          | 220Ω     | GND    |
| Green   | D4          | 220Ω     | GND    |

**Note:** Long leg (anode) → Arduino pin  
          Short leg (cathode) → resistor → GND

## ▶️ How to Run

### **Using Arduino IDE**
1. Open your Arduino project file (`.ino`)  
2. Connect your Arduino UNO  
3. Upload the code  
4. Build the circuit as shown above

### **Using Wokwi Online**
1. Create a new Arduino Uno project  
2. Paste your Arduino code into `sketch.ino`  
3. Add LEDs and resistors  
4. Start the simulation  

## 🎯 Purpose
This project is ideal for beginners learning:
- Arduino digital output  
- LED control  
- Timing and delays  
- Basic traffic signal logic  

