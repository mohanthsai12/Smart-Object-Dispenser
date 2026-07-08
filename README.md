# Smart Object Dispenser
An IoT-based Smart Object Dispenser that automatically dispenses products after successful UPI payment verification. The system integrates a web application, Firebase Realtime Database, and an ESP32 microcontroller to provide a real-time, cashless vending solution.

## Overview

The Smart Object Dispenser is an IoT-based automation project that enables cashless object dispensing using an ESP32 microcontroller, Firebase Realtime Database, and UPI payment integration. The system provides a simple and affordable alternative to traditional vending machines by combining cloud connectivity, embedded systems, and web technologies into a single automated solution. After a successful digital payment, the selected product is dispensed automatically without requiring any manual intervention. The project demonstrates the practical application of IoT in creating real-time, intelligent vending systems. :contentReference[oaicite:0]{index=0}

---

## Project Objective

The primary objective of this project is to design and develop a smart dispensing system capable of automating product delivery after payment confirmation. Unlike conventional vending machines that depend on expensive hardware and proprietary payment systems, this solution uses Firebase as a real-time communication platform and UPI as the payment gateway, making it cost-effective, scalable, and suitable for educational institutions, offices, and small businesses. :contentReference[oaicite:1]{index=1}

---

## How It Works

The system begins with a web-based application where users can browse the available products and select the desired item. After choosing a product, the application generates a UPI payment request that can be completed using any supported payment application such as Google Pay, PhonePe, or Paytm. Payment details, including the selected product and transaction status, are stored in Firebase Realtime Database. The ESP32 continuously monitors the database and automatically detects when the payment status changes to "Completed." Upon confirmation, it activates the corresponding servo motor and dispensing mechanism to release the selected product. Once dispensing is complete, the system updates the database status to "Dispensed," ensuring real-time synchronization between the software and hardware components. :contentReference[oaicite:2]{index=2}

---

## Key Features

The Smart Object Dispenser offers a modern cashless vending experience through UPI payment integration and cloud-based communication. The system features real-time synchronization using Firebase Realtime Database, automatic product dispensing through ESP32-controlled servo motors, a responsive web interface for product selection, secure transaction tracking, and a reliable embedded control mechanism. Its modular architecture also makes it easy to expand with additional products or advanced features in the future. :contentReference[oaicite:3]{index=3}

---

## Technologies Used

This project combines both hardware and software technologies to achieve real-time automation.

**Hardware**
- ESP32 Wi-Fi Microcontroller
- SG90 Servo Motors
- L298N Motor Driver
- DC Motor
- Relay Module
- 5V Power Supply

**Software**
- HTML
- CSS
- JavaScript
- Firebase Realtime Database
- Arduino IDE
- ArduinoJson Library

---

## System Architecture

The architecture consists of three primary layers. The presentation layer is a web application that allows users to browse products and initiate payments. The cloud layer uses Firebase Realtime Database to synchronize product information and payment status in real time. The embedded layer consists of an ESP32 microcontroller that continuously monitors Firebase and controls the servo motors responsible for dispensing products. This layered architecture ensures reliable communication between the user interface and the physical hardware. :contentReference[oaicite:4]{index=4}

---

## Applications

The Smart Object Dispenser can be deployed in educational institutions, offices, libraries, cafeterias, retail stores, hospitals, and other public spaces where affordable and automated product dispensing is required. Its cloud-connected architecture also makes it suitable for research and IoT learning environments. :contentReference[oaicite:5]{index=5}

---

## Future Scope

The project can be further enhanced by integrating automatic payment verification through official UPI APIs, inventory and stock monitoring, remote administrative dashboards, mobile application support, sales analytics, QR code scanning, multiple dispensing slots, and AI-based demand prediction. These improvements would make the system suitable for commercial deployment and large-scale vending applications. :contentReference[oaicite:6]{index=6}

---

## Conclusion

The Smart Object Dispenser demonstrates how IoT, cloud computing, and embedded systems can be integrated to create a reliable and cost-effective automated vending solution. By leveraging Firebase for real-time communication and the ESP32 for hardware control, the system provides secure, efficient, and cashless product dispensing. This project highlights the practical implementation of IoT technologies while offering a scalable foundation for future smart vending solutions. :contentReference[oaicite:7]{index=7}

---

## Contributors

**Darapu Mohanth Sai Dinesh Reddy**

SRM University AP

---

## License

This project is developed for educational and academic purposes.
