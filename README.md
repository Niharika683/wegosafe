# 🛡️ We Go Safe - Women Safety Application

We Go Safe is an Android-based women safety application designed to provide immediate assistance during emergency situations. The app enables users to quickly alert their trusted contacts by sending an SOS message along with their real-time location. Built using Android Studio, the application focuses on accessibility, speed, and reliability to enhance personal safety.

---

## 📌 Project Overview

Women's safety remains a significant concern in today's society. We Go Safe addresses this issue by offering an emergency response system that allows users to notify pre-configured emergency contacts instantly. In critical situations, users can simply shake their phone to trigger an SOS alert, eliminating the need to unlock the device or navigate through the application.

The application automatically retrieves the user's current location and sends it along with a help message to emergency contacts, ensuring that assistance can be reached as quickly as possible.

---

## 🚀 Features

* 📍 Real-Time Location Sharing
* 📱 Shake Detection for Emergency Alerts
* 🚨 One-Tap SOS Activation
* 📞 Emergency Contact Management
* 📩 Automatic SMS with Live Location
* 🔒 Simple and User-Friendly Interface
* ⚡ Fast Emergency Response Mechanism
* 📡 GPS-Based Location Tracking

---

## 🛠️ Technology Stack

| Component         | Technology                      |
| ----------------- | ------------------------------- |
| Platform          | Android                         |
| Language          | Java / Kotlin                   |
| IDE               | Android Studio                  |
| Location Services | Google Location API             |
| Communication     | SMS Manager                     |
| Sensors           | Accelerometer (Shake Detection) |

---

## 📂 Project Structure

```text
WeGoSafe/
│
├── app/
├── gradle/
├── res/
│   ├── layout/
│   ├── drawable/
│   └── values/
│
├── AndroidManifest.xml
├── build.gradle
└── README.md
```

---

## ⚙️ How It Works

1. User registers emergency contact numbers.
2. The application continuously monitors device shake events.
3. During an emergency, the user can shake the phone or trigger the SOS button.
4. The app fetches the user's current GPS location.
5. An emergency help message containing the live location link is automatically sent to registered contacts.
6. Contacts receive the alert and can quickly locate and assist the user.

---

## 📲 Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/WeGoSafe.git
```

### Open in Android Studio

1. Launch Android Studio.
2. Select **Open Existing Project**.
3. Choose the cloned project folder.
4. Sync Gradle files.

### Build and Run

1. Connect an Android device or start an emulator.
2. Click **Run ▶** in Android Studio.
3. Grant SMS and Location permissions when prompted.

---

## 🔐 Permissions Required

* ACCESS_FINE_LOCATION
* ACCESS_COARSE_LOCATION
* SEND_SMS
* READ_PHONE_STATE
* INTERNET

---

## 🎯 Future Enhancements

* Voice-Activated SOS Commands
* Emergency Audio Recording
* Live Location Tracking Dashboard
* Integration with Nearby Police Stations
* Push Notifications for Guardians
* AI-Based Threat Detection

---

## 👨‍💻 Developed By

**[Your Name]**

A mobile application focused on improving women's safety through instant emergency communication and location-sharing technology.

---

## 📄 License

This project is developed for educational and research purposes.

