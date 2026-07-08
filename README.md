# Fractal Antenna Design for Multiband Applications — Disaster Communication System

A disaster management and rescue communication system that uses vibration sensing, embedded microcontroller processing, and VANET (Vehicular Ad-hoc Network) communication to maintain connectivity when conventional networks fail during disasters.

## 📋 Overview

Natural disasters like earthquakes and tsunamis often destroy conventional communication infrastructure (cellular networks, base stations), delaying rescue coordination. This project proposes a resilient alternative: a vibration-sensing alert system combined with a VANET-based mesh network that operates without relying on commercial GSM/cellular networks.

## ✨ Key Highlights

- Real-time seismic vibration detection using vibration sensors
- PIC16F877A microcontroller (8K-word program memory) for signal processing and control
- RF wireless transmission for sensor-to-monitoring-station communication
- VANET-based ad-hoc mesh network — vehicles act as both transmitter and receiver nodes
- Achieves an effective communication range of 400m, with 90%+ message delivery within a 150m radius
- Operates independently of GSM/cellular infrastructure, remaining functional when conventional networks collapse

## 🛠️ Tech Stack / Hardware

- **Microcontroller:** PIC16F877A
- **Communication:** RF modules, RS-232, VANET/MANET protocols
- **Sensors:** Vibration sensors (seismic detection)
- **Circuit components:** MAX232, voltage regulators, relay drivers (ULN2003)
- **Simulation/Design tools:** MATLAB, AutoCAD

## 📐 System Architecture

1. **Module 1 — Sensing:** Vibration sensors detect seismic disturbances and transmit alert signals via wireless RF transmitters.
2. **Module 2 — Processing:** A PIC microcontroller receives sensor data, processes it, and relays it to a monitoring PC via RS-232.
3. **Module 3 — Network Relay:** When conventional networks fail, VANET nodes form a temporary ad-hoc mesh network to relay alerts and coordinate rescue response.

## 📈 Future Enhancements

- Integration of GPS for precise location tracking during disaster response
- Solar-powered/battery backup for extended field operation
- Expansion to support multiband fractal antenna hardware for improved range and connectivity

## 👤 Authors

**Mahalakshmi M** · **Niranjana Devi M**  
[LinkedIn](https://linkedin.com/in/maha434) · [GitHub](https://github.com/maha-434)

*Project submitted in partial fulfilment of B.E. Electronics and Communication Engineering, Prince Shri Venkateshwara Padmavathy Engineering College, Anna University.*
