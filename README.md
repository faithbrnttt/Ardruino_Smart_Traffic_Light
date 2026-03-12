<div align="center">

# 🚦 Arduino Smart Traffic Light System

### Embedded Systems • Smart Infrastructure • IoT Prototyping

A microcontroller-based traffic signal simulation designed to demonstrate how embedded systems control real-world infrastructure using sensors, timers, and automation logic.

---

👩‍💻 **Created by Faith Burnett**  
Full-Stack Developer • Data Engineering • Systems Integration  
🌐 https://faithb.dev

</div>

---

# Overview

The **Arduino Smart Traffic Light System** is a prototype that simulates the behavior of real-world traffic signals using a microcontroller and LED indicators.

The system cycles through traffic light states and can optionally incorporate sensors or timers to dynamically adjust signal timing.

Traffic signal simulations are commonly used as educational models for understanding how real traffic control systems operate and how embedded software manages hardware components. 

This project demonstrates:

• microcontroller programming  
• state-based control logic  
• LED device control  
• timing-based automation  
• basic smart city infrastructure concepts  

---

# System Architecture


Traffic Light LEDs
↓
Arduino Microcontroller
↓
Timing / State Logic
↓
Traffic Signal Output


The Arduino acts as the controller, cycling between **green, yellow, and red signals** to simulate real traffic light behavior.

---

# Key Features

### Traffic Signal Simulation

The system replicates the behavior of a standard traffic light:


Green → Yellow → Red → Repeat


Each light activates for a specific duration to simulate real intersection timing.

---

### Embedded Timing Control

The program uses microcontroller timers to control the duration of each traffic signal state.

Example timing sequence:

| Light | Duration |
|------|----------|
Green | 10 seconds |
Yellow | 3 seconds |
Red | 10 seconds |

---

### Hardware Device Control

The Arduino controls LED lights representing the traffic signals.

Each LED corresponds to a traffic state:

| LED | Meaning |
|----|--------|
Red | Stop |
Yellow | Prepare to stop |
Green | Go |

---

# Hardware Components

Example hardware used in this project:

| Component | Purpose |
|----------|---------|
Arduino Uno | Microcontroller controller |
Breadboard | Circuit prototyping |
Red LED | Stop signal |
Yellow LED | Warning signal |
Green LED | Go signal |
Resistors | Current control |
Jumper wires | Hardware connections |

Traffic light prototypes commonly use LEDs and microcontroller timing logic to replicate real traffic signals. :contentReference[oaicite:1]{index=1}

---

# Project Structure


Arduino_Smart_Traffic_Light

│
├── arduino_code
│ └── traffic_light.ino
│
├── circuit_diagram
│ └── wiring.png
│
└── README.md


---

# Tech Stack

| Category | Technology |
|--------|-------------|
| Microcontroller | Arduino |
| Language | C / Arduino |
| Hardware | LEDs, resistors, breadboard |
| Development Environment | Arduino IDE |

---

# Setup Instructions

### Install Arduino IDE

Download from:

https://www.arduino.cc/en/software

---

### Upload the Code

1. Connect the Arduino board to your computer
2. Open the `.ino` file in Arduino IDE
3. Select the correct board and port
4. Upload the firmware

---

# Example Control Logic

Example simplified Arduino logic:

```cpp
digitalWrite(greenLED, HIGH);
delay(10000);

digitalWrite(greenLED, LOW);
digitalWrite(yellowLED, HIGH);
delay(3000);

digitalWrite(yellowLED, LOW);
digitalWrite(redLED, HIGH);
delay(10000);
```

This sequence creates a repeating traffic signal pattern.

Example Traffic Flow

Green Light  → Traffic moves
Yellow Light → Prepare to stop
Red Light    → Traffic stops


The system continuously cycles through these states to simulate intersection control.

Use Cases

This project demonstrates concepts used in:

• embedded systems development
• traffic control automation
• smart city infrastructure
• microcontroller programming
• hardware-software integration

Future Improvements

Possible enhancements include:

• vehicle detection sensors
• pedestrian crossing buttons
• adaptive traffic signal timing
• IoT connectivity for remote monitoring
• smart city traffic analytics

Why I Built This

Modern transportation systems rely heavily on embedded control systems to manage traffic flow and reduce congestion.

This project explores how microcontrollers can simulate traffic control systems and demonstrates the interaction between hardware and software in embedded environments.

It reflects my interest in:

• embedded systems
• IoT infrastructure
• automation systems
• smart city technologies

Author
Faith Burnett

Full-Stack Developer
Data Engineering • Systems Integration

🌐 Portfolio
https://faithb.dev

💻 GitHub
https://github.com/faithbrnttt

🔗 LinkedIn
https://www.linkedin.com/in/faithbdev

---




<div align="center">

⭐ If you found this project interesting, feel free to star the repo!

</div>
