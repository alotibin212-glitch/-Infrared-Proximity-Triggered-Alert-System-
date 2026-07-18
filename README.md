# 🚨 Infrared Proximity-Triggered Alert System

An automated hardware prototype designed to detect proximity using infrared technology. The system triggers an immediate audible and visual alert when an object is detected within the sensor's range.

---

## 📊 System Architecture
The system operates through a reliable analog circuit logic:
* Infrared Sensing: The IR proximity sensor continuously monitors for reflected light from nearby objects.
* Switching Core: A BC557 transistor functions as an electronic switch, activated by the sensor's output signal.
* Alert Mechanism: Upon detection, the transistor completes the circuit, energizing both the buzzer for sound and the LED for visual indication.

<img width="725" height="1280" alt="4444" src="https://github.com/user-attachments/assets/b9c16cd1-edf4-436c-bf84-108e9d263a7f" />


---

## 🔌 Circuit Specifications
The prototype is constructed on a solderless breadboard using the following components:
* IR Proximity Sensor: Detection module.
* BC557 Transistor: Switching component.
* Buzzer: Audible alarm output.
* LED Indicator: Visual alarm output.
* Resistors: 220Ω (LED protection) and 1kΩ (base current limiting).
* Power Source: 9V Battery.

---

## 💻 Operating Principle
1. Standby Mode: The circuit remains inactive while the IR sensor detects no obstruction.
2. Trigger State: When an object enters the sensor range, the sensor sends a signal to the base of the BC557 transistor.
3. Execution: The transistor switches "ON," allowing current to flow through the buzzer and LED simultaneously.

---

## 👤 Developer
* Eng. Noura Abbad Al-Qathami 
