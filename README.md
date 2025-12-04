# Smart Bus Entry, Fare & Seat Management System (Hardware Project)


A smart bus system to automate fare collection and seat management using Arduino and RFID technology.

## Features
- Passenger authentication via RFID cards
- Automatic fare deduction and balance update
- Real-time seat and standing availability on LCD
- Servo-controlled gate for entry and exit
- Simple keypad interface for destination selection and balance recharge

## Hardware Components
- Arduino Uno R3  
- MFRC522 RFID Module  
- 4x4 Keypad  
- 20x4 LCD Display (I2C)  
- Servo Motor  
- IR Sensors

## How It Works
1. Scan RFID card for identification and balance verification.  
2. Select destination using keypad.  
3. System calculates fare and assigns seat or standing slot.  
4. LCD displays fare, balance, and slot status.  
5. Servo opens/closes gate automatically.

