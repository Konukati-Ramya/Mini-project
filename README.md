## Smart Blood Bank Management System using IoT
## 📌 Overview

The Smart Blood Bank Management System leverages IoT technology to enhance the safety, efficiency, and reliability of blood bank operations. Traditional blood banks face issues such as:

-Improper storage conditions

-Manual record-keeping

-Lack of real-time monitoring

-Blood wastage and shortages

This project addresses these challenges by integrating sensors, Arduino, and cloud platforms to continuously monitor temperature, humidity, and inventory levels in blood banks. Real-time alerts and data visualization ensure that stored blood remains safe and available when needed.

## 🚀 Features

-IoT-based Monitoring: Sensors track temperature (2–6°C), humidity (40–60%), and weight of blood bags.

-Real-time Alerts: Notifications triggered if values deviate from safe ranges.

-Cloud Integration: Data sent to ThingSpeak for real-time monitoring and visualization.

-Anomaly Detection: Detects irregular conditions and sensor malfunctions.

-Demand Prediction: Forecasts blood demand using historical data with Linear Regression/ARIMA.

Remote Access: Medical staff can monitor storage conditions anytime, anywhere.

🏗️ System Architecture

## Hardware Components:

1.Arduino

2.HX711 Sensor (Weight measurement)

3.DHT11 Sensor (Temperature & Humidity)

4.ESP01 Wi-Fi Module

## Software Components:

1.Operating System: Windows 11

2.Arduino IDE

3.ThingSpeak (IoT Cloud Platform)

4.SQLite (Data Storage)

## 📊 System Design

1.Use Case Diagram

2.Class Diagram

3.Sequence Diagram

4.Activity Diagram

(Refer to the /docs folder for detailed diagrams and project workflow.)

## ⚙️ Working Principle

-Sensors capture real-time data (temperature, humidity, weight).

-Data transmitted via MQTT protocol to ThingSpeak & stored in SQLite.

-Anomaly detection functions check for unsafe conditions.

-Alerts sent when thresholds are breached.

-Demand prediction models analyze historical blood demand data.

-Results displayed on dashboards for quick decision-making.

## ✅ Results

1.Real-time monitoring reduces risk of blood spoilage.

2.Improved accuracy in inventory management.

3.Early detection of sensor failures.

4.Supports healthcare systems with safe, reliable, and accessible blood supply.

## 📝 Conclusion

-This IoT-powered Smart Blood Bank Management System transforms the way blood banks operate by:

-Ensuring safe storage conditions

-Reducing wastage

-Improving efficiency

-Enhancing patient safety and healthcare quality

## 📂 Repository Structure
├── /code          # Source code (Arduino + Python scripts)
├── /docs          # Project documentation & diagrams
├── /data          # Sample datasets for demand prediction
├── /results       # Experimental outputs & logs
└── README.md      # Project overview

## Output:

<img width="1920" height="1080" alt="Screenshot 2024-12-19 191156" src="https://github.com/user-attachments/assets/6d439e71-4e33-4b56-bb83-ef5eb31a5ce4" />


<img width="1920" height="1080" alt="Screenshot 2024-12-19 191632" src="https://github.com/user-attachments/assets/3a7721b4-a610-4458-b949-c06dcec6f90c" />



## 🔮 Future Enhancements

-Integration with Blockchain for secure donor & recipient data management.

-AI-based prediction models for optimizing inventory and donor outreach.

-Mobile application for real-time access to blood stock information.
