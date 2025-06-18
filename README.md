# 🛠 CNC Navigator App

The **CNC Navigator App** is a mobile application developed using **Android Studio** that provides real-time, remote control for **CNC (Computer Numerical Control)** machines using **Bluetooth (HC-05)** communication. The app is designed with modern Material UI and features Firebase Authentication for secure access, customizable feedrate control, and safety features such as emergency stop.

---

## 📲 Features

- 🔐 **Firebase Authentication** (Email/Password)
- 📶 **Bluetooth Connectivity** with HC-05 module
- 🎮 **Directional Control** for CNC (X and Y axes)
- 📏 **Feedrate Adjustment** (10–2000 units)
- 🛑 **Emergency Stop** functionality
- ✨ **Splash Screen** with branding animation
- 📱 **Modern Material Design UI**

---

## 🎯 Project Overview

The CNC Navigator App is built for CNC operators, DIY enthusiasts, and educational users who want a flexible and portable CNC control system. By using Bluetooth communication and a simple, responsive UI, the app eliminates the need for bulky CNC panels.

---

## 🔐 User Authentication

- Firebase-based login system
- Email/Password login
- Password reset feature
- (Google Sign-In coming soon)

---

## ⚙️ System Architecture

### 🔹 `SplashActivity`
- Launch screen with fade-in animation

### 🔹 `LoginActivity`
- Handles user authentication via Firebase

### 🔹 `HomeActivity`
- Main screen with directional controls, feedrate input, and emergency stop

### 🔹 `MainActivity`
- Placeholder for future feature expansion

---

## 🛠 Development Environment

| Component         | Details                       |
|------------------|-------------------------------|
| IDE              | Android Studio                |
| Language         | Java                          |
| Min SDK Version  | API 21 (Lollipop)             |
| Target SDK       | API 33+                       |
| Libraries        | Firebase Auth, Bluetooth API, Material Components |

---

## 📁 File Structure

  CNCNavigatorApp/
├── app/
│ ├── java/com/yourpackage/
│ │ ├── SplashActivity.java
│ │ ├── LoginActivity.java
│ │ ├── HomeActivity.java
│ │ └── MainActivity.java
│ ├── res/
│ │ ├── layout/
│ │ │ ├── activity_splash.xml
│ │ │ ├── activity_login.xml
│ │ │ ├── activity_home.xml
│ └── AndroidManifest.xml
├── .gitignore

 ## Challenges Faced
🔐 Bluetooth Permissions in Android 12+
📶 Bluetooth Disconnections
✅ Input Validation for feedrate
📱 UI Compatibility across screen sizes

## 🌱 Future Enhancements
Google Sign-In integration
Z-axis movement support
Two-way CNC feedback via Bluetooth
Multi-CNC machine profiles
UI themes and customizations

## Screenshots
  ![WhatsApp Image 2025-06-17 at 11 39 19_33da99e1](https://github.com/user-attachments/assets/db78847a-2b10-474e-8502-520b36d75da1)

![WhatsApp Image 2025-06-17 at 11 39 33_a8d3b3c1](https://github.com/user-attachments/assets/ccdd6ecf-2d5e-4ba6-a109-a2addcfa2ce6)

![WhatsApp Image 2025-06-17 at 11 39 44_a044b161](https://github.com/user-attachments/assets/1121c90d-1715-429a-b2e4-76e4cd070efd)
