# VitaSense: A Real-Time Health Monitoring Technology

**Tags:** `IoT`, `Hardware`, `C++`, `ESP32`, `Blynk`, `Sensor Integration`, `Project Report`

> A real-time, multi-sensor health monitoring system that sends data to the Blynk IoT platform for remote visualization.

---
<img width="741" height="473" alt="Image" src="https://github.com/user-attachments/assets/537a76df-821d-4664-8803-bc32f06fff99" />

## 1. The Problem

Continuous and remote monitoring of a patient's vital signs (heart rate, SpO2, temperature) is crucial for modern healthcare. Building a low-cost, connected (IoT) device that can reliably measure multiple parameters and display them remotely is a common engineering challenge.

## 2. Our Solution

For our "Sistem Embedded Biomedik" final project, our team (Kelompok 3) developed **VitaSense**. This device integrates three different sensors (DHT11, DS18B20, and MAX30102) with an **ESP32** microcontroller.

The ESP32 reads the sensor data in real-time, processes it, and transmits it via Wi-Fi to the **Blynk IoT platform**. This allows for a live, remote dashboard where a user can monitor the patient's vital signs from a phone or web browser. The system also includes a buzzer for local alerts if vitals fall out of a safe range.

## 3. My Role & Key Contributions

I was a **Developer and Hardware Integrator** on this team project.

* Wrote and debugged the `C++` (Arduino IDE) code for integrating the DHT11 (humidity/temp), DS18B20 (precise temp), and MAX30102 (heart rate/SpO2) sensors.
* Implemented the logic to send sensor data to the Blynk server.
* Helped design and build the physical circuit prototype and PCB layout.
* Co-authored the final project report, which includes the full system design and source code.

## 4. Technology Stack

* **Programming Language:** `C++` (Arduino)
* **Hardware:** `ESP32`, `DHT11`, `DS18B20`, `MAX30102`, `Buzzer`
* **Software & Platforms:** `Arduino IDE`, `Blynk IoT Platform`

## 5. Proof & Key Results

* **[Report & Code]:** The complete 34-page project report, which includes the **full `C++` source code** in the appendix, is located in this repository.
    * **[Project Report Sistem Embedded_Kelompok 3]**

## 6. Project Status

**Status: [Complete]**
*This project was successfully completed for the Sistem Embedded Biomedik course.*
