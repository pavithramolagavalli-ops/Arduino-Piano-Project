# 🎹 Arduino Piano - 4 Key Musical Keyboard

A functional 4-key piano built with Arduino UNO that plays Sa, Re, Ga, Ma notes. Complete with TinkerCAD simulation, circuit diagram, and source code.

### ▶️ **LIVE DEMO - TRY IT NOW!**
**👉 [Click here to Play My Arduino Piano on TinkerCAD](https://www.tinkercad.com/things/af2nN91AwZT-cool-blad-trug)**

**How to test:** 
1. Click the link above
2. Press `Start Simulation` button
3. Click the 4 buttons to play musical notes Sa, Re, Ga, Ma

---

### 📸 **Project Demo**

**circuit diagram:**
![Circuit Diagram](circuit.png)

**TinkerCAD Simulation:**
![Simulation Screenshot](Screenshot%202026-06-03%20092555.png)

---

### ✨ **Features**
- **4 Musical Notes:** Plays Sa (C4), Re (D4), Ga (E4), Ma (F4) using `tone()` function
- **Real-time Response:** Push button = Instant sound output
- **Debounced Input:** Clean note triggering without false signals
- **Beginner Friendly:** Simple circuit with detailed comments in code

---

### 🛠️ **Hardware Components**
| **Component** | **Quantity** | **Purpose** |
| --- | --- | --- |
| Arduino UNO R3 | 1 | Main microcontroller |
| Push Buttons | 4 | Keys for Sa, Re, Ga, Ma |
| Piezo Buzzer | 1 | Sound output |
| 10kΩ Resistors | 4 | Pull-down for buttons |
| Breadboard + Wires | 1 Set | Circuit connections |

---

### 🔌 **Circuit Connections**
| **Arduino Pin** | **Connected To** |
| --- | --- |
| Pin 2 | Button 1 - Sa Note |
| Pin 3 | Button 2 - Re Note |
| Pin 4 | Button 3 - Ga Note |
| Pin 5 | Button 4 - Ma Note |
| Pin 8 | Buzzer Positive |
| GND | All button grounds + Buzzer negative |

> **Full circuit diagram:** `circuit.png` file in this repo

---

### 💻 **Software & Code**
- **Language:** Arduino C/C++
- **IDE:** Arduino IDE / TinkerCAD Circuits
- **Main File:** `Arduino-Piano.ino`
- **Key Functions Used:** `pinMode()`, `digitalRead()`, `tone()`, `noTone()`

---

### 🚀 **How to Run This Project**

#### **Option 1: TinkerCAD Simulation**
1. Click the **Live Demo** link at top
2. Press `Start Simulation`
3. Click buttons to play

#### **Option 2: Real Hardware**
1. Download `Arduino-Piano.ino` from this repo
2. Connect components as per circuit diagram
3. Upload code via Arduino IDE
4. Press buttons to play music

---

### 📚 **What I Learned**
- Reading digital inputs with `digitalRead()`
- Generating sound frequencies using `tone()` function
- Building pull-down resistor circuits for buttons
- Debugging circuits using TinkerCAD simulation
- Writing clean, commented Arduino code

---

### 🎯 **Future Improvements**
- [ ] Add all 7 notes Sa Re Ga Ma Pa Dha Ni
- [ ] Record and playback functionality
- [ ] LED feedback for each key press
- [ ] Switch to capacitive touch instead of buttons

---

### 👩‍💻 **Author**
**Pavithra Molagavelli**  
B.Tech ECE Student | IoT & Embedded Systems Enthusiast

📧 **Contact:** pavithramolagavalli@gmail.com  
🔗 **LinkedIn:** https://www.linkedin.com/in/pavithra-molagavelli-1st-613906326  
💼 **Open to:** Internships in Embedded Systems / IoT

---

**⭐ If you like this project, give it a star!**  
**🎹 Made with Arduino + Music + Lot of Debugging**


---

0
