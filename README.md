# 🔐 Multi-Factor Cloud Authentication System

A modern, cloud-based authentication platform that enhances account security using **Multi-Factor Authentication (MFA)**, **Google OAuth**, **device tracking**, and **adaptive trust scoring** — all managed through a unified dashboard.

---

## 📌 Overview

This project provides a **secure and user-friendly authentication system** designed for real-world cloud applications. It combines:

* Traditional email/password login
* Social login via Google OAuth
* Multi-Factor Authentication (MFA)
* Device & session monitoring
* Trust-score based risk analysis

The system helps detect suspicious activities early and gives users full control over their account security.

---

## 🚀 Key Features

* 🔑 Email & Password Authentication
* 🌐 Google OAuth Login
* 🔐 Multi-Factor Authentication (MFA) with backup codes
* 📊 Trust Score System (adaptive risk analysis)
* 📱 Device Tracking & Management
* 🕒 Session Monitoring & Control
* ⚠️ Failed Login Attempt Alerts
* 📜 Login History Tracking
* 🎨 Light/Dark Theme Toggle
* ⚙️ Account Settings Management

---

## 🧠 Trust Score System

An intelligent **risk-based scoring mechanism**:

* Each failed login attempt reduces the user's trust score
* Gradual score drop helps identify suspicious behavior
* Enables proactive security monitoring
* Can be extended for adaptive authentication

---

## 🛠️ Tech Stack

### Frontend

* ⚛️ React
* 📘 TypeScript
* 🎨 Tailwind CSS
* 🧩 shadcn/ui

### Backend & Authentication

* ☁️ Supabase Auth
* 🗄️ PostgreSQL (via Supabase)

---

## 🏗️ Architecture

### Core Components

* **Frontend:** React + TypeScript UI
* **Backend/Auth:** Supabase (Authentication + Database)

### Database Tables

* `profiles` → User profile data
* `devices` → Registered user devices
* `login_attempts` → Login logs & failed attempts
* `user_sessions` → Active session tracking

---

## 🔐 Security Features

* Multi-Factor Authentication (MFA)
* Session Management (active session control)
* Device Tracking (unknown device detection)
* Login Attempt Logging
* Trust Score Risk Analysis
* OAuth-based secure login

---

## ⚙️ Demo Flow (Presentation Ready)

1. Open application → Login page
2. Sign in using email/password or Google OAuth
3. View dashboard:

   * Devices
   * Failed Attempts
   * Trust Score
4. Show login history & failed attempt alerts
5. Navigate to:

   * Profile → Account Settings
6. Show:

   * MFA toggle
   * Backup codes
7. View:

   * Active sessions
   * Device management
8. Toggle light/dark theme
9. Logout → Login again (consistency check)

---

## 📂 Project Structure

```id="k92nsa"
project-root/
│
├── src/                 # React frontend
├── components/          # UI components
├── pages/               # App pages (Login, Dashboard, Settings)
├── supabase/            # Supabase config & queries
├── styles/              # Tailwind styles
│
└── README.md
```

---

## 🎯 Objectives

* Provide secure authentication system
* Simulate real-world cloud security architecture
* Enable user-level control over sessions and devices
* Detect and prevent suspicious login behavior

---

## ⚠️ Limitations

* Requires internet (cloud-based system)
* Basic trust scoring (can be enhanced with AI/ML)
* Depends on Supabase services

---

## 🔮 Future Enhancements

* 🤖 AI-based anomaly detection
* 📲 SMS/Email OTP integration
* 🔑 Biometric authentication
* 🌍 Multi-region deployment
* 📊 Advanced security analytics dashboard

---

## 💡 Use Cases

* Cloud-based applications
* SaaS platforms
* Enterprise authentication systems
* Secure login systems

---

## 👨‍💻 Author

**Dhruv Patel**
B.Tech CSE (Cloud Technology & Information Security)

---

