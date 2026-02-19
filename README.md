# 🌍 IoT Based Air Pollution Monitoring System  
## Project Title: Lack of Real-Time Pollution Tracking

## 📌 Overview
Air pollution is a major environmental issue caused by industrial emissions, vehicle exhaust, and human activities. Traditional air quality monitoring systems are expensive and limited to specific locations.

This project presents an **IoT-based Air Quality Monitoring System** that continuously monitors air pollution levels in real time using gas sensors and a Wi-Fi-enabled microcontroller. The system displays data locally and remotely via a cloud platform.

---

## 🎯 Objectives

- Continuous monitoring of air pollution levels  
- Detection of harmful gases in the environment  
- Real-time air quality data display  
- Remote monitoring using internet connectivity  
- Low-cost and user-friendly design  
- Raise awareness about environmental pollution  

---

## 🛠️ Hardware Components Used

- **MQ-135 Air Quality Sensor**
  - Detects CO₂, NH₃, smoke, alcohol, benzene
  - Operating Voltage: 5V

- **ESP32 / Arduino Microcontroller**
  - Controls system operation
  - Built-in Wi-Fi (ESP32)

- **DHT11 / DHT22 Sensor**
  - Measures temperature and humidity
  - Operating Voltage: 3.3V – 5V

- **OLED / LCD Display**
  - Displays real-time air quality data

- **Wi-Fi Module**
  - Enables cloud communication

- **5V Power Supply**
  - Power bank or adapter

- **Acrylic Enclosure**
  - Protects system components

---

## 💻 Software Requirements

- Arduino IDE  
- Embedded C / Arduino Programming  
- Cloud IoT Platform (ThingSpeak / Blynk / Firebase etc.)  

---

## ⚙️ Working Methodology

1. Sensors detect air pollutants (CO, smoke, harmful gases, temperature & humidity).
2. Microcontroller reads sensor values.
3. Data is processed and compared with pollution thresholds.
4. Processed data is sent to cloud via Wi-Fi.
5. Air quality data is displayed on mobile/web dashboard.
6. Alert is generated if pollution exceeds safe levels.

---

## 🧠 Design Thinking Approach

### Empathize
Identified lack of real-time air quality awareness among students and residents.

### Define
Need for low-cost, portable, real-time monitoring system with remote access.

### Ideate
Generated ideas including mobile-based systems, wearable sensors, and fixed monitoring stations.

### Prototype
Developed working model using gas sensors, microcontroller, and cloud dashboard.

### Test
System successfully detected pollution levels and generated alerts in real time.

---

## 📊 Results & Analysis

- Real-time air quality updates
- Accurate gas detection
- Stable Wi-Fi data transmission
- Quick response to environmental changes
- Reliable and consistent performance

---

## ✅ Advantages

- Real-time monitoring  
- Remote access from anywhere  
- Low-cost and easy installation  
- Compact and portable  
- Scalable for large-area deployment  

---

## 🔮 Future Enhancements

- Integration of additional gas sensors  
- Dedicated mobile application  
- AI-based pollution trend prediction  
- GPS-based pollution tracking  
- Smart city deployment  

---

## 📚 References

1. Research papers on IoT-based environmental monitoring  
2. Gas sensor datasheets  
3. Microcontroller documentation  
4. Online technical resources  

---

## 👨‍💻 Developed By
Department of ISE  
CMR Institute of Technology  
Academic Year: 2025-26

---

## 📷 Project Files Included

- Source Code  
- Hardware Setup Images  
- User Feedback Forms  
- System Documentation  

---

## 🚀 How to Run the Project

1. Connect sensors to ESP32/Arduino as per circuit diagram.
2. Upload the code using Arduino IDE.
3. Connect Wi-Fi credentials in the code.
4. Power the system.
5. Monitor real-time data on cloud dashboard.

---

⭐ If you found this project useful, feel free to give it a star!


