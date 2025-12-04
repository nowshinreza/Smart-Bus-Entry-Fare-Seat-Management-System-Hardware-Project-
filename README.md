# Smart Bus Entry, Fare & Seat Management System (Hardware Project)

## Overview
This hardware project automates ticketing, fare deduction, and seat allocation in public transport using Arduino, RFID cards, keypad, LCD, servo motor, and IR sensors. It provides real-time passenger monitoring and secure gate control, improving convenience, safety, and efficiency in bus operations.

## Features
- **RFID-based Authentication:** Scan cards to validate passengers and manage balances.
- **Automated Fare Deduction:** Fare calculated based on distance and seat/stand selection.
- **Seat & Stand Allocation:** Real-time tracking of available seats and standing slots using IR sensors.
- **Gate Control:** Servo motor opens and closes gates automatically for authorized passengers.
- **LCD Display:** Shows fare, balance, seat assignment, and system status.
- **Manual Controls:** Keypad allows recharging balance or controlling gate manually.

## Hardware Components
- Arduino Uno R3
- MFRC522 RFID Module
- 4x4 Keypad
- 20x4 LCD Display (I2C)
- Servo Motor
- IR Sensors
- Power Supply & Breadboard for wiring

## Workflow
1. Passenger scans RFID card.
2. System checks balance and allows recharge if needed.
3. Passenger selects destination via keypad.
4. Fare is calculated and deducted.
5. System assigns seat/stand if available.
6. Gate opens automatically via servo motor.
7. LCD displays fare, balance, and slot information in real-time.

## Future Improvements
- GPS integration for automatic stop detection.
- Mobile app for ticket recharge and live bus tracking.
- Dynamic fare based on route length.
- Voice alerts for visually impaired passengers.
- Cloud-based fare and passenger analytics.

## Expected Outcome
- Efficient, secure, and convenient ticketing.
- Real-time monitoring of passengers.
- Automated seat allocation and gate management.

