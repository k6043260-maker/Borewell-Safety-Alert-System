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

  ## Working Principle

The Borewell Safety Alert System works as follows:

1. **System Start**
   - The system starts when the power supply is switched on.

2. **Power Initialization**
   - NodeMCU, GPS module, GSM module, and buzzer are powered and initialized.

3. **GPS Initialization**
   - The GPS module acquires satellite signals and starts providing real-time latitude and longitude coordinates.

4. **GSM Initialization**
   - The GSM module connects to the cellular network and prepares to send SMS alerts.

5. **Load Geo-Fence**
   - The predefined safe-zone coordinates and radius are loaded into the NodeMCU.

6. **Location Monitoring**
   - The system continuously reads the current GPS location.

7. **Geo-Fence Check**
   - The current location is compared with the predefined geo-fence.

8. **Inside Safe Zone**
   - If the child is within the safe boundary, the system continues monitoring.

9. **Outside Safe Zone**
   - If the child crosses the geo-fence, the system detects a danger condition.

10. **Activate Alarm**
    - The buzzer is activated to warn nearby people.

11. **Send SMS Alert**
    - The GSM module sends an SMS containing the child's live GPS location to the registered guardian.

12. **Wait and Monitor**
    - The system waits for 30 seconds before checking again to avoid repeated alerts.

13. **Panic Button Monitoring**
    - The panic button is continuously monitored.

14. **Emergency Mode**
    - If the panic button is pressed, the system immediately enters emergency mode.

15. **Emergency SMS**
    - An emergency SMS with the current GPS location is sent instantly.

16. **Continuous Alert**
    - The buzzer remains active until the emergency condition is resolved.

---

## Author

**Khushi A**

Electronics and Communication Engineering Student

GitHub: https://github.com/k6043260-maker
