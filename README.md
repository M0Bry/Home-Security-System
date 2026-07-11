# Smart Home Security System

A Smart Home Security System built with **Arduino Uno** that provides secure access control and intrusion detection using a keypad authentication mechanism, sensors, an LCD display, LEDs, and an audible alarm.

The project demonstrates how embedded systems can be used to improve residential security through real-time monitoring and automated threat detection.

---

## Features

- Password-based door authentication
- Intrusion detection
- LCD status display
- Keypad user interface
- Motion and obstacle monitoring
- Green/Red LED status indicators
- Audible buzzer alarm
- Real-time system feedback
- Arduino-based embedded control
- Modular hardware design

---

## System Workflow

1. Power on the security system.
2. The LCD prompts the user to enter the security password.
3. The keypad receives the entered password.
4. If the password is correct:
   - Access is granted.
   - Green LED indicates success.
   - LCD displays an authorized message.
5. If the password is incorrect:
   - Access is denied.
   - Red LED turns on.
   - Buzzer alarm is activated.
6. Sensors continuously monitor the protected area.
7. Any detected intrusion immediately triggers the alarm system.

---

## Hardware Components

- Arduino Uno
- 4×4 Matrix Keypad
- 16×2 LCD Display
- Buzzer
- Green LED
- Red LED
- Ultrasonic Sensor
- PIR Motion Sensor (if installed)
- Jumper Wires
- Breadboard
- MDF Smart House Model

---

## Software

- Arduino IDE
- Embedded C++
- Keypad Library
- LiquidCrystal_I2C Library
- Arduino Core Libraries

---

## Project Structure

```
Smart-Home-Security/
│
├── Home_Security_System.ino
├── README.md
├── LICENSE
└── Project Photos/
```

---

## Applications

- Smart Home Automation
- Home Security
- Embedded Systems Education
- IoT Prototyping
- Arduino Learning Projects
- Security Demonstrations

---

## Future Improvements

- RFID Authentication
- Fingerprint Sensor
- Mobile App Control
- ESP32 Wi-Fi Connectivity
- Cloud Monitoring
- CCTV Integration
- GSM SMS Alerts
- Face Recognition
- Mobile Notifications
- Voice Assistant Integration

---

## Author

**Mohamed AlBry**

Faculty of Computer Science and Artificial Intelligence

---

## License

Licensed under the MIT License.
