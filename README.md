# Mechanical-Ventilator-Arduino

A low-cost, portable mechanical ventilator designed for emergency and resource-limited settings. The ventilator is controlled using an Arduino Uno and Raspberry Pi, utilizing a DC motor and pressure sensors for airflow regulation. This project aims to provide an affordable, open-source alternative for medical use, especially in remote areas.

# Features

✔ Portable and Affordable – Designed with cost-effective components
✔ Arduino & Raspberry Pi Integration – Controls motor speed and monitors pressure
✔ Real-Time Monitoring – Collects and visualizes breathing data
✔ Customizable Breathing Cycles – Adjustable Inspiration-to-Expiration (I:E) ratio and Frequency Rate (FR)

# Hardware Requirements
 • Arduino Uno (for sensor interfacing)
 • Raspberry Pi (any model with GPIO support)
 • DC Motor with PWM Control
 • Pressure Sensor (e.g., MPX5010DP)
 • LCD Display (optional, for real-time monitoring)
 • Push Buttons & Potentiometer (for adjusting settings)
 • Power Supply (12V for motor, 5V for control circuits)

# Software Requirements
 • Arduino IDE (for flashing the Arduino)
 • Python 3.x (for Raspberry Pi control)
 • Raspberry Pi OS (Linux-based, tested on Raspberry Pi)

# How to Use

1. Setup the Hardware
 • Connect the Arduino Uno to the pressure sensor and DC motor
 • Use Raspberry Pi GPIO to control motor speed using PWM signals
 • Refer to the circuit diagram in the Docs folder

2. Flash the Arduino
 • Upload arduino_code.ino to the Arduino Uno using the Arduino IDE

3. Run the Python Script
 • Connect Raspberry Pi to the Arduino via USB
 • Execute the script on Raspberry Pi:
      • The ventilator will begin monitoring pressure and controlling airflow

4. Data Logging & Visualization
 • The script logs pressure data in Datos3.txt
 • visualize the breathing cycle

# Future Improvements
 • Add touchscreen interface for real-time control
 • Implement AI-based breathing pattern detection
 • Optimize power efficiency for battery-operated models
