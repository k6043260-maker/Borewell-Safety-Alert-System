# Borewell Safety Alert System

## Project Overview

The Borewell Safety Alert System is an IoT-based project developed to improve child safety around open and abandoned borewells. The system uses NodeMCU (ESP8266), GPS, and GSM technologies to monitor a predefined safety zone. If a child enters the restricted area, the system sends an SMS alert with the live GPS location to the guardian and activates a buzzer.

---

## Objectives

- Prevent accidents near open borewells.
- Send instant emergency alerts.
- Provide real-time GPS location.
- Increase child safety using IoT technology.

---

## Features

- GPS-based Geo-fencing
- GSM SMS Alert
- Real-time Location Tracking
- Buzzer Alert
- Portable IoT Device
- Low-cost Safety Solution

---

## Hardware Components

- NodeMCU ESP8266
- NEO-6M GPS Module
- SIM800L GSM Module
- Piezo Buzzer
- Push Button
- Lithium Battery
- Connecting Wires

---

## Software Used

- Arduino IDE
- Embedded C/C++
- TinyGPS++ Library
- SoftwareSerial Library

---

## Working

1. Power ON the system.
2. GPS continuously reads the current location.
3. A geo-fence boundary is created.
4. When the child crosses the boundary:
   - GPS obtains the location.
   - GSM sends an SMS to the guardian.
   - Buzzer turns ON.
5. The guardian receives the child's location through Google Maps.

---

## Project Structure

```text
Arduino_Code/
Circuit_Diagram/
Block_Diagram/
Flowchart/
Hardware_Images/
Output/
Report/
README.md
```

---

## Future Enhancements

- Mobile Application
- Cloud Database
- AI-based Monitoring
- Solar Power Support
- Camera Integration

---

## Author

**Khushi A**

Electronics and Communication Engineering Student

GitHub: https://github.com/k6043260-maker
