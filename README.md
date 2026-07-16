# Dashboard-smart-trafic-
# ESP32 IoT monitoring &amp; Traffic Light System

<img width="1324" height="751" alt="Capture d&#39;écran 2026-07-16 102951" src="https://github.com/user-attachments/assets/2e5f4dab-33c8-4794-b1b9-e70ace8bf863" />

An IoT project using an ESP32 to monitor environmental conditions and control a traffic light system in real time.  The system combines :  
-an ultrasonic sensor (HC-SR04)  
-a soil moisture sensor  
-a DHT11 sensor for temperature and humidity readings  
-a three-color traffic light (green/yellow/red)  

# Circuit wiring :

<img width="881" height="644" alt="image" src="https://github.com/user-attachments/assets/9f428a70-5a73-45a8-ab4b-47d79d098ff1" />

All sensor data is transmitted via MQTT to a Node-RED server, which powers a live web dashboard displaying gauges, historical charts, and real-time status — accessible locally through the local browser

# Node-Red flow presentation :
<img width="666" height="585" alt="Capture d&#39;écran 2026-07-16 102941" src="https://github.com/user-attachments/assets/759be1f3-9dc4-4bf3-ab65-16fba06aceeb" />
