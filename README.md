# Fingerprint-Based-Exam-Hall-Authentication

This project implements a fingerprint-based authentication system for exam hall security using an Arduino Uno and an R307 fingerprint sensor. The system aims to prevent impersonation and ensure only authorized students access the examination premises by verifying their identities through biometric fingerprint recognition. It can store upto 10 different Finger IDs.
**Software Requirements**
Arduino IDE: For writing and uploading the code.
Libraries:
Adafruit_Fingerprint: For interfacing with the R307 fingerprint sensor.
LiquidCrystal: For controlling the LCD display.
RTClib: For managing the DS3231 RTC module.
EEPROM: For storing fingerprint IDs and attendance data.
SoftwareSerial: For serial communication with the fingerprint sensor.
Hardware Requirements
Arduino Uno: Microcontroller for processing and interfacing.
R307 Fingerprint Sensor: For capturing and verifying fingerprints.
Jumper wires.
