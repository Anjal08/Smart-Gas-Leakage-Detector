# Smart-Gas-Leakage-Detector
IoT-based Gas Leakage Detection with Auto Cut-off Regulator, SMS &amp; Call Alert System using GSM Module and MQ-2 Sensor

🚨 Gas Leakage Detection and Auto Cut-off Regulator with Call & SMS Alert
📌 Overview

This project is an IoT-based Gas Leakage Detection System designed to ensure safety by detecting gas leaks (LPG/CO) and taking immediate action.
The system:

Detects gas leakage using an MQ-2 sensor.

Automatically cuts off the gas supply using a relay-controlled regulator.

Sends SMS and Call alerts to the registered mobile number via a GSM module.

Triggers a buzzer alarm and displays status on LCD (optional).

This project can be deployed in households, industries, and restaurants to prevent fire accidents and save lives.

⚡ Features

✅ Real-time gas leakage detection
✅ Auto shut-off regulator for safety
✅ SMS & Call alert using GSM module
✅ Buzzer alert for nearby warning
✅ Low-cost and easy to implement
✅ Scalable for industrial use

🛠️ Hardware Requirements

Arduino UNO / NodeMCU / ESP8266

MQ-2 Gas Sensor

GSM Module (SIM800L / SIM900) with SIM card

Relay Module (to control regulator/solenoid valve)

Solenoid Valve / Gas Regulator

Buzzer & LED indicators

Power Supply (5V/12V depending on setup)

LCD Display (optional)

💻 Software Requirements

Arduino IDE

Required Libraries:

SoftwareSerial.h

LiquidCrystal.h (if LCD used)

🔌 Circuit Diagram

📷 (Insert your circuit diagram image here)

Example:

circuit/
   ├── gas-leakage-circuit.png
   ├── fritzing-diagram.fzz

⚙️ Working Principle

The MQ-2 sensor continuously monitors the gas level.

If gas concentration exceeds the threshold:

The buzzer turns ON.

Relay cuts off the gas regulator.

GSM Module sends SMS & makes a call to the user.

Once gas levels return to normal, system resets automatically.

🚀 Getting Started
🔹 Setup Instructions

Clone this repository:

git clone https://github.com/your-username/Gas-Leakage-Detection-Auto-Cutoff.git


Open code in Arduino IDE.

Install required libraries.

Connect hardware components as per circuit diagram.

Upload code to Arduino.

Insert SIM card into GSM module.

Power the system and test with a lighter (carefully).

📽️ Demo Video

📹 (Insert your project demo video link here – YouTube/Google Drive)

🔮 Future Scope

Mobile App integration for real-time alerts

Cloud connectivity (Firebase/ThingSpeak/IoT dashboard)

AI-based gas leakage prediction

Integration with Fire Alarm Systems

👨‍💻 Contributors

Your Name – Developer

📜 License

This project is licensed under the MIT License – feel free to use and modify.

✨ This project aims to increase home & industrial safety by combining IoT + Embedded Systems for accident prevention.
