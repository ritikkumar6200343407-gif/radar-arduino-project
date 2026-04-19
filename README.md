# 📡 Construction of Radar Using Arduino

A sonar-based radar system built using Arduino UNO, HC-SR04 Ultrasonic Sensor, and SG-90 Servo Motor. The system detects objects within a 2–3 meter range and displays real-time results on a radar-type graphical interface using Processing IDE.

---

## 🎯 Objective

- Detect obstacles using an Ultrasonic Sensor and Arduino UNO
- Display real-time object detection on a radar-type visual screen using Processing IDE / MATLAB
- Useful for security, accident prevention, and object tracking applications

---

## ⚙️ Components Used

### Hardware
| Component | Description |
|---|---|
| Arduino UNO | Microcontroller (ATmega328, 16 MHz) |
| HC-SR04 | Ultrasonic Sensor — detects objects 2cm to 400cm |
| SG-90 Servo Motor | Rotates 0° to 180° for radar sweep |
| Breadboard | For circuit connections |
| Bluetooth Cable | Connects Arduino to computer |
| Jump Wires | For wiring components |

### Software
| Tool | Purpose |
|---|---|
| Arduino IDE | Writing and uploading code to Arduino |
| Processing IDE | Graphical radar display |
| MATLAB | Alternative for signal visualization |

---

## 🔧 How It Works

1. The **SG-90 Servo Motor** sweeps from **0° to 180°** and back continuously.
2. The **HC-SR04 Ultrasonic Sensor** is mounted on top of the servo motor and sweeps along with it.
3. The sensor emits ultrasound at **40,000 Hz** and measures the time taken for the echo to return.
4. Distance is calculated based on the speed of sound and travel time.
5. The data is sent to **Processing IDE**, which renders a live **radar-type display** on screen.
6. If an object is detected within the range, it is **highlighted on the graphical display**.

---

## 🖥️ Circuit Diagram

```
Arduino UNO
  ├── Pin 9  → Servo Motor (SG-90) Signal Wire (Orange)
  ├── 5V     → Servo Motor VCC (Red) + HC-SR04 VCC
  ├── GND    → Servo Motor GND (Brown) + HC-SR04 GND
  ├── Pin 10 → HC-SR04 TRIG
  └── Pin 11 → HC-SR04 ECHO
```

---

## 📐 Applications

- 🚗 Driverless vehicle / obstacle avoidance systems
- 🛡️ Security and surveillance systems
- 🛸 Military and defense (air defense, missile guidance)
- 🚢 Navigation and ship security
- 🛰️ Remote sensing and space satellites
- 🔍 Speed detection of moving objects

---

## 📊 Results

- Object detection range: **2 to 3 meters**
- Servo sweep: **0° to 180°**
- Real-time graphical display using Processing IDE
- Future upgrade possible using **LiDAR** technology for extended range

---

## 👨‍💻 Team Members

| Name | Roll Number |
|---|---|
| Ritik Kumar | 22116109010 |
| Arun Kumar | 22116109048 |
| Rohit Kumar | 22116109005 |
| Priyanshu Kumar | — |

**Institution:** Nalanda College of Engineering, Chandi
**University:** Bihar Engineering University
**Course:** B.Tech — Aeronautical Engineering
**Year:** 2025–2026

---

## 📚 References

- https://howtomechatronics.com/projects/arduino-radar-project
- https://electronicsforu.com/videos-slideshows/videos/constructing-radar-Arduino
- http://microcontrollerslab.com/servo-motor-control-and-interfacing-with-Arduino
- Translation Bureau (2013). "Radar definition". Public Works and Government Services Canada.

---

## 📄 License

This project was developed for academic purposes at Nalanda College of Engineering.
Feel free to use or reference it for educational use.
