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

![Slide33](https://github.com/user-attachments/assets/bcf2b825-0fdf-4d67-adaa-897092d92dbe)
![Slide32](https://github.com/user-attachments/assets/5ea50eec-cdbc-45de-9278-46eea79177fb)
![Slide31](https://github.com/user-attachments/assets/b9a1e5f5-888a-4e26-8a61-6525c4134803)
![Slide30](https://github.com/user-attachments/assets/c81efe62-8a6c-4a6b-b0f3-6c51867aecaf)
![Slide29](https://github.com/user-attachments/assets/c5039eb7-24fd-4d08-9c2d-c35b1b97dea9)
![Slide28](https://github.com/user-attachments/assets/5f00e3ed-557d-47bb-a814-d4b72ba0195b)
![Slide27](https://github.com/user-attachments/assets/131990e9-1902-461b-8998-a025292bb0d4)
![Slide26](https://github.com/user-attachments/assets/9fd95f1b-6000-4abf-8ea0-0ab2db911efb)
![Slide25](https://github.com/user-attachments/assets/a81d392d-ea33-49d5-b07b-547d9eddc5b1)
![Slide24](https://github.com/user-attachments/assets/b5a024d2-5958-4c3b-b02a-65ea60077ab3)
![Slide23](https://github.com/user-attachments/assets/0c9181fb-bd20-4bee-827a-aa61350ad596)
![Slide22](https://github.com/user-attachments/assets/02335f06-af97-4d38-8693-c589350919c8)
![Slide21](https://github.com/user-attachments/assets/cbebb031-1146-4c4b-81ce-ad382ba8412a)
![Slide20](https://github.com/user-attachments/assets/173c5a1e-81d5-4c34-9bda-22595849940d)
![Slide19](https://github.com/user-attachments/assets/deee7356-c6b4-42ab-ac6b-e5d2a4f3370b)
![Slide18](https://github.com/user-attachments/assets/4a3a10e2-ec74-4341-bd7f-4e07aae3259b)
![Slide17](https://github.com/user-attachments/assets/fc613301-af39-4b28-b544-f9c7a0377412)
![Slide16](https://github.com/user-attachments/assets/d5a9e6bd-d357-4fc7-b1b7-c7c7a655bafc)
![Slide15](https://github.com/user-attachments/assets/2937d3d5-1a9d-4cf8-bd2e-c6b574888b86)
![Slide14](https://github.com/user-attachments/assets/8bd790eb-012f-4c56-b629-8aea3ec79dc8)
![Slide13](https://github.com/user-attachments/assets/587a9a4b-a32f-406e-81a6-a1837f983f23)
![Slide12](https://github.com/user-attachments/assets/32733608-ec63-4b04-b82f-5dd6882df46a)
![Slide11](https://github.com/user-attachments/assets/ecf67d87-febb-4db1-bf9e-a37333f4798d)
![Slide10](https://github.com/user-attachments/assets/a8cde4ee-a758-4892-935e-6044b0b5a34a)
![Slide9](https://github.com/user-attachments/assets/c71366b1-5c3d-4f7b-bc51-53be28fc5f32)
![Slide8](https://github.com/user-attachments/assets/db106381-12e1-4325-8327-f082a6160eee)
![Slide7](https://github.com/user-attachments/assets/892a8408-529b-425c-a44f-a60f993df03d)
![Slide6](https://github.com/user-attachments/assets/54b304f3-9031-494f-ad0d-6fe2449c9dad)
![Slide5](https://github.com/user-attachments/assets/09b309c2-fc6f-4a9a-82e1-1f6bc2d450e4)
![Slide4](https://github.com/user-attachments/assets/5510163b-b903-4555-a90c-dbb9b6f9e609)
![Slide3](https://github.com/user-attachments/assets/9eb629d1-0a91-462b-82bd-e00e001896ba)
![Slide2](https://github.com/user-attachments/assets/b99cb2af-e07b-4123-88f0-d9d1bd55eb2d)
![Slide1](https://github.com/user-attachments/assets/77c61170-98bf-4d6e-aef4-76b642e3df6c)


<div align="center">

⭐ If you found this project interesting, feel free to star the repo!

</div>
