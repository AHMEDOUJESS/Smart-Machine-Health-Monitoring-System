# 🛠️ Smart-Machine-Health-Monitoring-System - Monitor Machines in Real Time

[![Download Now](https://img.shields.io/badge/Download-Smart--Machine--Health--Monitoring--System-brightgreen?style=for-the-badge&logo=github)](https://github.com/AHMEDOUJESS/Smart-Machine-Health-Monitoring-System)

---

## 📌 Overview

The Smart Machine Health Monitoring System helps track industrial machines using sensors. It collects temperature, vibration, and sound data from machines. You can see this data on a live dashboard. This system aims to detect problems before they cause machine failures. The project uses common technology like Arduino and IoT platforms.

This tool shows how to monitor machines for better maintenance and fewer breakdowns.

---

## ⚙️ How It Works

1. Sensors measure machine temperature, vibration, and sound.
2. A microcontroller (Arduino or ESP32) reads the sensor data.
3. The data is sent to an online cloud service called ThingSpeak.
4. The online dashboard updates in real time to show machine status.
5. Users watch the dashboard to spot unusual machine behavior.

This system helps catch early signs of trouble and avoid unexpected downtime.

---

## 🛠️ What You Need (Hardware)

* Arduino UNO or ESP32 microcontroller
* DHT11 temperature sensor
* Vibration sensor module
* Sound sensor module
* ESP8266 WiFi module
* Breadboard and jumper wires to connect parts

These parts connect physically. The microcontroller reads sensors and sends information through WiFi.

---

## 💻 System Requirements

* Windows 10 or later (64-bit recommended)
* Internet access for live data updates
* USB port to connect Arduino or ESP32
* Web browser (Chrome, Firefox, Edge) for viewing dashboard

No special software or programming skills are needed to run the application.

---

## 🚀 Getting Started

1. Download the project from the green Download button at the top or click:
   https://github.com/AHMEDOUJESS/Smart-Machine-Health-Monitoring-System

2. Extract the downloaded file to a folder you can find easily.

3. Connect your hardware:
   - Plug sensors into the microcontroller using jumper wires and breadboard.
   - Connect the microcontroller to your PC using a USB cable.

4. Install Arduino IDE (if you plan to load code on the microcontroller):
   Download from https://www.arduino.cc/en/software and follow installation steps.

5. Open the Arduino IDE and load the firmware code from the project folder.

6. Upload the code to your microcontroller.

7. Once uploaded, the device will start sending data to the online dashboard.

8. Open a web browser and go to the ThingSpeak dashboard URL provided in the project documentation or code comments.

9. Watch the machine data in real time.

---

## 🔧 Installing and Running the Software on Windows

The software component is designed to show the data and help monitor machines. Follow these steps:

1. Visit the project page to download the files needed:
   https://github.com/AHMEDOUJESS/Smart-Machine-Health-Monitoring-System

2. Look for a folder named `Windows_App` or similar inside the downloaded files.

3. If there is an executable `.exe` file, double-click it to launch the app.

4. If the app requires installation, open the installer and follow the prompts.

5. Connect your hardware to the PC and ensure it is powered.

6. The app will automatically connect to the cloud service and begin displaying live data.

7. Use the dashboard controls to filter or analyze machine conditions.

---

## 🧐 Monitoring Dashboard Features

* Live data graphs for temperature, vibration, and sound
* Alerts for abnormal readings
* Historical data for troubleshooting
* Easy-to-read status indicators
* Refreshes every few seconds without manual updates

These features help you track machine health and spot issues early.

---

## 🎯 Objectives

The Smart Machine Health Monitoring System aims to:

* Track industrial machine parameters all the time.
* Detect abnormal behavior automatically.
* Prevent unexpected machine failures.
* Provide a clear, real-time status display.

---

## ⚙️ Technologies Behind the System

The project uses:

* Arduino or ESP32 microcontrollers for sensor reading.
* Sensors: DHT11 (temperature), vibration sensors, and sound sensors.
* ESP8266 WiFi module to send data to the internet.
* ThingSpeak IoT cloud platform to store and display data.
* Embedded C programming for microcontroller code.
* Git and GitHub for code management.

---

## 🔌 Connecting the Hardware

1. Attach the DHT11 temperature sensor to the microcontroller analog pin.
2. Connect the vibration sensor output to a digital pin.
3. Attach the sound sensor module to an analog or digital input.
4. Connect the ESP8266 WiFi module to the microcontroller using serial pins (TX/RX).
5. Use jumper wires and a breadboard to organize connections.
6. Supply power to the microcontroller either via USB or external source.

Make sure all connections are secure before powering on.

---

## 🗂️ File Structure Inside the Download

- `/Firmware/`  
  Contains code for Arduino or ESP32.

- `/Dashboard/`  
  Files for the ThingSpeak dashboard setup.

- `/Windows_App/`  
  Windows application files and executables.

- `/Docs/`  
  Manuals and instructions.

---

## ⚠️ Troubleshooting Common Issues

* If the app does not open, check your Windows security settings.
* Make sure the microcontroller is connected and powered.
* Confirm that sensor wires are in correct pins.
* Verify your PC has internet access.
* Reload or update Arduino IDE if uploading firmware fails.
* Restart the ThingSpeak dashboard if it does not update.

---

## 🚩 Download and Setup Link

Download the full project here:

[![Download Now](https://img.shields.io/badge/Download-Smart--Machine--Health--Monitoring--System-blue?style=for-the-badge&logo=github)](https://github.com/AHMEDOUJESS/Smart-Machine-Health-Monitoring-System)

This link takes you to the GitHub page. Click "Code" then "Download ZIP" to get the entire system files. Unzip and follow the sections above to set up hardware and software on Windows.