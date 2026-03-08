# RFID Asset Tracking System

This project uses Arduino UNO and MFRC522 RFID module to track assets.

## Components Used
- Arduino UNO
- MFRC522 RFID Reader
- RFID Card / Tag
- Buzzer
- Red LED
- Green LED
- Breadboard
- Resistors

## Working
1. RFID reader scans the RFID card.
2. Arduino reads the UID from the card.
3. If the UID matches the authorized UID:
   - Green LED ON
   - Buzzer Beep
4. If UID does not match:
   - Red LED ON

## Simulation
This project was simulated using Wokwi Simulator.

## Files in this Repository
- sketch.ino → Arduino program
- diagram.json → Circuit diagram
- libraries.txt → Required libraries
