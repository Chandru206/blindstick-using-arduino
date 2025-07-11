# Smart Blind Stick 🚶‍♂️ using Arduino Uno

This project simulates a Smart Blind Stick designed for visually impaired individuals.  
It uses an **ultrasonic sensor** to detect obstacles and provides real-time feedback via **a buzzer and an LED**.

Built using:
- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- Active Buzzer
- LED with 220Ω Resistor

---

## 🔗 Live Simulation  
🎮 [Click here to run the project on Wokwi](https://wokwi.com/projects/436178318759622657)

---

## 🧠 How It Works

The HC-SR04 sensor measures distance to nearby obstacles.

| Distance (in cm) | Behavior                          |
|------------------|-----------------------------------|
| ≤ 5 cm           | 🔴 LED ON + 🔊 Buzzer ON (alert)   |
| > 5 cm           | ⚫ LED OFF + 🔇 Buzzer OFF          |

- The buzzer and LED provide an alert when any obstacle is **5cm or closer** to the sensor.
- Values are printed to Serial Monitor for debugging.

---

## 💾 Files Included

| File Name     | Purpose                           |
|---------------|-----------------------------------|
| `sketch.ino`  | Arduino source code                |
| `project.json`| Wokwi circuit configuration        |
| `README.md`   | Project overview and usage info    |

---

## 💡 Ideal Use Case

This project is ideal for:
- Engineering students
- IoT beginners
- Arduino hobbyists working on assistive devices

---

## 📜 License

Open-source under MIT License.  
Feel free to use and modify with credit.
