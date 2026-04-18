# ECE-Engineering-Project
A collection of electronics projects from my 2nd year at SRMIST, including an ESP32 Oscilloscope and Laser Audio system.

# My Electronics & Communication Engineering Portfolio

## 1. ESP32 Digital Oscilloscope (CRO)
A functional oscilloscope built using an ESP32.
* **Features:** 1Msps sampling rate, dual-core RTOS implementation, and a 1.69" TFT display.
* **Key Components:** ESP32, TFT Display, and Analog Front-end (AC/DC coupling).

A functional oscilloscope built using an ESP32 that captures and displays waveforms in real-time.
* **Features:** 1Msps sampling rate, dual-core RTOS implementation, and a 1.69" TFT display.
* **Components Required:**
    * ESP32 Microcontroller (Dual-core)
    * 1.69" Round TFT Display (240x280)
    * Resistors: 100kΩ (R4), 10kΩ (R5) for the voltage divider
    * Capacitor: 0.1µF (C1) for AC coupling
    * Push Buttons: 4 (OK, Plus, Minus, Back)
    * BNC Connector for probe input

## 2. Wireless Audio Transfer via Laser
A Li-Fi concept project that transmits sound through a light beam.
* **How it works:** Audio is modulated via a PAM8403 amplifier into a laser diode and received by a solar panel.
* **Advantage:** Immune to electromagnetic interference (EMI).

A Li-Fi concept project demonstrating the transmission of sound through a modulated light beam.
* **How it works:** Audio signals are amplified and used to modulate the intensity of a laser diode, which is then captured by a solar panel.
* **Components Required:**
    * Laser Diode (Transmitter source) 
    * PAM8403 Audio Amplifier Module 
    * Solar Panel (Receiver/Light sensor) 
    * 9V Battery (Power supply) 
    * Speaker (Audio output) 
    * 1kΩ Resistor (Protection/Biasing) 

## 3. Traffic Light Control System
A sequential logic circuit designed using a 555 Timer and 4017 Decade Counter.
* **Logic:** The 555 timer provides clock pulses to sequence Red, Yellow, and Green LEDs.

A sequential logic circuit that mimics real-world traffic signal behavior without microcontrollers.
* **Logic:** A 555 timer generates clock pulses that drive a 4017 decade counter to sequence the LEDs.
* **Components Required:**
    * 555 Timer IC (Pulse generator) 
    * 4017 Decade Counter IC (Main sequencer) 
    * 1N4148 Diodes (x6) 
    * LEDs: Red, Yellow, and Green 
    * Potentiometer: 1MΩ (Timing control) 
    * Resistors: 100kΩ, 22kΩ, and 330Ω 
    * Capacitors: 1µF and 2.2mF 
