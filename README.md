# 🛡️ AI-Driven Login Anomaly Detection System

This project is a **real-time AI-powered cybersecurity system** that monitors login behavior and detects anomalies such as brute force attacks, 
failed login spikes, and suspicious access locations. It uses **machine learning (Isolation Forest)** 
and automation to create Jira tickets and send security alerts via email — improving response speed and reducing human error.

---

## 🚀 Features

- Detects abnormal login activity (e.g., failed login spikes, unusual login times)
- Tracks IP address, timestamps, and login success/failure
- Uses **Isolation Forest** for unsupervised anomaly detection
- Automatically creates a **Jira ticket** for any detected threat
- Sends **email alerts** to the security team
- Stores user and login logs securely in **MongoDB**
- Built with a full stack: **React.js + Node.js + MongoDB + Python**

---

## 🛠️ Installation & Setup

### 🔧 Requirements

- Node.js & MongoDB installed
- Python 3.x with `pandas` and `scikit-learn`
- Jira account with REST API access
- Email credentials for NodeMailer

---

## ⚙️ Backend Setup

```bash
npm install
node server.js

👨‍💻 Author
Ali Hannan Muhammad Nasim
Student ID: L38886685
University Academy 92
