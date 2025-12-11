# 🔧 Vladislav Kudenko — Hardware & Embedded Portfolio

Welcome to my hardware & embedded systems engineering portfolio.
This repository contains my PCB designs, electronics projects, embedded firmware, hardware testing notes, and photos of assembled prototypes.

I specialize in:

* PCB design (2–4 layers, digital & mixed-signal)
* Embedded firmware (Arduino, ESP32, RP2040, STM32 basics)
* Power electronics & low-noise design practices

---

## 👤 Contact

* **Email:** [vladislavkudenko1@gmail.com](mailto:vladislavkudenko1@gmail.com)
* **LinkedIn:** [https://www.linkedin.com/in/vladislav-kudenko](https://www.linkedin.com/in/vladislav-kudenko)
* **Location:** Open to relocation within the U.S.

---

# 📂 Projects

---

## 🖥️ 1. RP2040 Dev Board (Custom Design)

**A custom, hand-designed development board based on the Raspberry Pi RP2040 microcontroller.**
This is a fully standalone board featuring USB-C power input, onboard voltage regulation, QSPI flash memory, crystal oscillator, and castellated pins for module-style integration.

### ✔ Features

* Raspberry Pi **RP2040 microcontroller** (Dual-core Arm Cortex-M0+) 
* **TPS54202** LDO for stable 3.3V regulation 
* **USB-C** connector for power and USB data interface with ESD protection
* **W25Q128JV** 128-Mbit QSPI Flash Memory for program storage 
* **12 MHz Crystal Oscillator** (ABM8-272-T3) with 15pF load capacitors 
* **Full breakout of all 30 GPIO pins**
* **Castellated edge pads** for surface-mount module applications 
* Power LED + user LED on GPIO0
* SWD header for programming & debugging
* Reset and Boot buttons
* Reverse-polarity protection diodes on V_IN and V_USB inputs 

### 📁 Folder

`/rp2040_dev_board/`
(Contains: schematic PDF, Gerbers, PCB layout, renders)

---

## 🔌 2. Breadboard Power Supply (3.3V / 5V)

A compact dual-voltage breadboard power module designed for prototyping and portable projects.

### ✔ Includes

* Schematic
* 2-layer PCB layout
* Gerber files
* 3D board renders

### ✔ Features

* USB-C + DC-barrel jack input
* Reverse-polarity protection
* Selectable **3.3V / 5V** rails
* Power LEDs
* PI filters + bulk capacitors (≈20% ripple reduction)

📁 Folder: `/breadboard_power_supply/`

---

## 🦼 3. Smart Wheelchair — Graduation Project

An Arduino-based semi-autonomous mobility system with multi-input control and obstacle avoidance.

### ✔ Documentation Includes

* System block diagram
* Wiring and electronics documentation
* Firmware
* Prototype photographs

### ✔ Technical Highlights

* HC-SR04 sonar obstacle detection (~95% accuracy)
* IBT-2 H-bridge motor controller
* Voice + joystick dual-input control
* Team-based prototyping & testing

📁 Folder: `/smart_wheelchair/`

---

## 🔊 4. TPA6017A2 Stereo Audio Amplifier

A low-noise, small-form-factor stereo audio amplifier board.

### ✔ Includes

* Full schematic
* PCB layout (Gerbers + render)
* High-quality 3D board images

### ✔ Features

* TPA6017A2 amplifier IC
* Gain-selectable pads
* Clean analog layout with proper grounding & decoupling

📁 Folder: `/audio_amplifier/`

---

# 📸 Gallery & Photos

Photos of assembled prototypes, oscilloscope captures, and hardware tests are included inside the project folders.

---

# 📄 License

This portfolio is provided for personal & professional reference.
You may use design ideas freely, but full project files are licensed under the repository’s selected license (see LICENSE).

---

# 🙌 Thanks for visiting!

If you're interested in collaboration or hiring, feel free to reach out.
