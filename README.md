# 👨‍🦯 Smart Blind Stick using Arduino Uno

This project simulates a smart blind stick built for visually impaired individuals.  
Using an **HC-SR04 ultrasonic sensor**, it detects nearby obstacles and gives real-time feedback through a **buzzer and blinking LED** — both change based on how close an object is.

---

## 🔗 Live Simulation  
🎮 [Try the live demo on Wokwi](https://wokwi.com/projects/436178318759622657)

---

## 📐 How It Works

The HC-SR04 sensor continuously measures the distance to obstacles.

Based on that distance:

| Distance to Object | LED Behavior         | Buzzer Behavior       |
|--------------------|----------------------|------------------------|
| ≤ 5 cm             | Constant ON          | Continuous beep        |
| 6 – 15 cm          | Fast blinking        | Fast pulse beeping     |
| 16 – 30 cm         | Slow blinking        | Slow beep              |
| > 30 cm            | OFF                  | Silent                 |

- Both LED and buzzer are **pulse-controlled** to help the user sense how close the obstacle is.
- All distances are measured in real-time and printed to the Serial Monitor.

---

## 🧰 Components Used

- Arduino Uno R3  
- HC-SR04 Ultrasonic Sensor  
- Buzzer (active)  
- LED + 220Ω resistor  
- Breadboard & jumper wires

---

## 💾 Project Files

| File           | Description                            |
|----------------|----------------------------------------|
| `sketch.ino`   | Arduino logic with proximity behavior  |
| `project.json` | Circuit setup for Wokwi simulation     |
| `README.md`    | This file                              |

---

## 💡 Use Case

Ideal for:
- Assistive technology demos  
- Arduino beginners  
- Academic or portfolio projects  
- Hands-on learning in embedded systems

---

## 📃 License

This project is open-source (MIT License).  
Feel free to modify and build upon it for educational or personal use.

---
