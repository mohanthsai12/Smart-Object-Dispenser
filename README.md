# Smart-Object-Dispenser
An IoT-based Smart Object Dispenser that automatically dispenses products after successful UPI payment verification. The system integrates a web application, Firebase Realtime Database, and an ESP32 microcontroller to provide a real-time, cashless vending solution.

🛒 Smart Object Dispenser

An IoT-based Smart Object Dispenser that automatically dispenses products after successful UPI payment verification. The system integrates a web application, Firebase Realtime Database, and an ESP32 microcontroller to provide a real-time, cashless vending solution.

🚀 # Features
🌐 Web-based user interface
📱 UPI payment support (Google Pay, PhonePe, Paytm)
☁️ Firebase Realtime Database integration
⚡ Real-time communication between web app and ESP32
🤖 Automatic product dispensing using servo motors
📊 Payment status tracking
🔄 Automatic status update after dispensing
🛠️ Tech Stack
Hardware
ESP32
SG90 Servo Motors (3x)
L298N Motor Driver
DC Motor
Relay Module
5V Power Supply
Software
HTML
CSS
JavaScript
Firebase Realtime Database
Arduino IDE
ESP32
ArduinoJson Library
📋 System Architecture
User
   │
   ▼
Web Application
   │
HTTP (JSON)
   ▼
Firebase Realtime Database
   │
HTTP (JSON)
   ▼
ESP32
   │
   ├── Servo 1
   ├── Servo 2
   └── Servo 3
⚙️ Working
User opens the web application.
Products are loaded from Firebase.
User selects items and proceeds to payment.
A UPI QR/link is generated.
After payment, the user confirms the transaction.
Firebase updates the payment status to Completed.
ESP32 continuously monitors Firebase.
ESP32 activates the corresponding servo motor.
Product is dispensed.
Firebase updates the status to Dispensed.
📂 Project Structure
Smart-Object-Dispenser/
│
├── frontend/
│   ├── index.html
│   ├── style.css
│   └── script.js
│
├── esp32/
│   └── SmartObjectDispenser.ino
│
├── firebase/
│   └── firebaseConfig.js
│
├── images/
│
├── README.md
└── LICENSE
🔧 Hardware Connections
Component	ESP32 Pin
Servo 1	GPIO 13
Servo 2	GPIO 12
Servo 3	GPIO 14
L298N IN1	GPIO 25
L298N IN2	GPIO 26
Relay	GPIO 33
📸 Demo

Add screenshots here:

Home Page
Product Selection
Payment Screen
Firebase Database
ESP32 Serial Monitor
Product Dispensing
🎯 Applications
Smart vending machines
Educational institutions
Offices
Retail stores
Cafeterias
Libraries
🔮 Future Enhancements
Inventory management
Automatic payment verification via UPI APIs
Mobile application
QR code scanning
Product stock alerts
Admin dashboard
Multiple vending slots
Sales analytics
📖 Installation
Clone the Repository
git clone https://github.com/yourusername/Smart-Object-Dispenser.git
Frontend
Configure Firebase credentials.
Open index.html or host using Firebase Hosting.
ESP32
Install Arduino IDE.
Install ESP32 Board Package.
Install required libraries:
Firebase ESP Client
ArduinoJson
Servo Library
Update Wi-Fi credentials.
Upload the code to ESP32.
👨‍💻 Contributors
Darapu Mohanth Sai Dinesh Reddy
Team Members
📜 License

This project is developed for educational purposes at SRM University AP.

⭐ Support

If you found this project useful, consider giving the repository a ⭐ Star on GitHub!
