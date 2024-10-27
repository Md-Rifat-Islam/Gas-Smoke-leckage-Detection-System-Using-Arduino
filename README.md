# Gas-Smoke-leckage-Detection-System-Using-Arduino
![System Outlook](https://github.com/Md-Rifat-Islam/Gas-Smoke-leckage-Detection-System-Using-Arduino/assets/73377455/6037bce1-32fb-4f0b-aa96-0d9fed4a8ee8)
**Overview**
This project is an Arduino-based system designed to detect gas and smoke leakage. It uses various sensors to monitor air quality and alert users in case of hazardous gas levels, aiming to enhance safety in homes, offices, and industrial settings.

**Features**
Gas and Smoke Detection: Detects harmful gases such as methane, propane, and smoke.
Real-Time Monitoring: Continuously monitors air quality and updates readings in real-time.
Alert System: Triggers an alarm and LED light when gas levels reach a dangerous threshold.
User-Friendly Display: Shows gas concentration and alert status on an LCD.
**Components Used**
Arduino UNO
Gas sensor (MQ-2)
Smoke sensor (optional if using MQ-2, which covers both gas and smoke)
Buzzer for alerts
LED indicators
LCD display (16x2 or similar)
Power supply (9V battery)
**Circuit Diagram**
![Inner Circuit Diagram](https://github.com/Md-Rifat-Islam/Gas-Smoke-leckage-Detection-System-Using-Arduino/assets/73377455/4902ee61-765f-477b-8cfa-305317adc0bd)

**Usage**
The system will automatically begin monitoring for gas and smoke.
If gas levels exceed the threshold, the buzzer will sound, and the LED will light up as an alert.
The LCD will display the current gas concentration.
How It Works
This project utilizes the MQ-2 gas sensor, which is sensitive to LPG, methane, and smoke. The sensor outputs an analog signal that is converted by the Arduino to determine the gas concentration in the air. When the concentration exceeds a predefined safe level, the system triggers the alert mechanisms.

**Future Improvements**
Wi-Fi Integration: Use an ESP8266 or ESP32 for remote monitoring and notifications.
Battery Backup: Add a rechargeable battery for emergency power.
Mobile App Notifications: Integrate with an IoT platform to send notifications to a mobile app.

Contact
For any questions or feedback, feel free to reach out:
email: "rifat010bushra@gmail.com"
