# SmartSwitch – Touch based Smart switch board System

SmartSwitch is an IoT-based smart classroom automation system developed using ESP32, Blynk REST API, HTML, CSS, and JavaScript. It provides a centralized web interface to control and monitor classroom devices.

https://youtu.be/WBlNAlx0u4M?si=d4let_A9e-9cdHGH

## 🎯 Objective

The main objective of SmartSwitch is to create a centralized and intelligent classroom control system that allows users to control classroom appliances remotely while providing automation through smart modes, schedules, timers, and presence detection.

## 📝 Problem Statement

* Traditional classrooms require manual operation of multiple switches.

* Lights, fans, and projectors cannot normally be controlled from a single interface.

* Appliances may remain ON when the classroom is empty.

* There is no centralized real-time monitoring of classroom devices.

* Conventional switchboards generally do not provide timers or scheduling.

* Teachers/users cannot conveniently control devices remotely.

## ✨ Features
### 🔷 Modern UI

1. Modern, responsive, and user-friendly dashboard.
2. Displays the current status of connected devices.
3. Provides controls for lights, fans, and projectors.
4. Shows system connectivity and presence status.
5. Built using pure HTML, CSS, and JavaScript without frameworks.

### 📡 Remote-Based Control

1. Commands from the web UI are sent through the Blynk REST API.
2. ESP32 receives the device state and controls the corresponding relay.
3. Device states can be synchronized between the physical system and web dashboard.

### 🧠 Smart Modes

Modes instantly apply selected lights:

* 📽️ Projector Mode – Custom selection.

* 👨‍🏫 Teaching Mode – All Lights ON.

* 🌱 Energy-Saver Mode – Custom selection.

### 📶 Wi-Fi Configuration

### 📡 Wi-Fi Configuration Manager

- Add, edit, and delete saved Wi-Fi networks.
- Scan nearby networks using ESP32.
- Select and apply Wi-Fi configurations.
- Set a default network for automatic connection.
- Manage ESP32 Wi-Fi connection from the web UI.

### ⏱️ Schedules & Timers

* Automatically control devices for a specific duration.

* Schedule appliances to turn ON or OFF at predefined times.

* Useful for automating classroom routines.

* Helps prevent devices from being left ON unnecessarily.

Example :-

```
08:30 → Lights ON
08:35 → Fan ON
09:00 → Teaching Mode
13:00 → Energy Saver
14:00 → Teaching Mode
17:00 → All Devices OFF
```

For reliable clock-based automation.

### 👤 Presence Detection

* Uses a PIR sensor to detect motion/activity in the classroom.

* Presence information is sent to the ESP32 and can be synchronized with Blynk.

* Can be used to trigger automation such as energy-saving operation when no motion is detected for a configured period.
 
## 📌 Requirements

### Hardware:

* ESP32 Dev Module
* Relay board (8-channel)
* PIR sensor
* RCWL radar presence sensor

### Software:

* Web browser (Chrome recommended)
* Blynk IoT account (Cloud)
* ESP32 firmware with correct V-pin mapping

## 🛠️ Technology Stack
| Category	     |   Technology   |
|----------------|----------------|
| Microcontroller| 	ESP32         |
| Programming	 | Arduino        |
| API	         | Blynk REST API |
| Frontend       | 	HTML5         |
| Styling	     | CSS3           |
| Logic	         | JavaScript     |
| Communication  | 	Wi-Fi         |
| Sensors	     | PIR / Touch    |
| Output	     | Relay Module   |


## 🔮 Future Scope

* Energy consumption monitoring
* Dedicated mobile application
* Voice control
* Multi-classroom management
* Usage analytics

---
