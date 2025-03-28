# 🔐 Location & OTP Authentication System

## 🌟 Project Highlights

![Security Badge](https://img.shields.io/badge/Security-Enhanced-green)
![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Flask](https://img.shields.io/badge/Flask-Framework-red)

### 🚀 Advanced Two-Factor Authentication Solution

Revolutionize your authentication approach with a cutting-edge system that combines **geographic intelligence** and **dynamic password verification**. 

## 📡 Key Features

- **🌍 Intelligent Location Tracking**
  Restrict access based on predefined geographic boundaries, adding an unprecedented layer of security.

- **🔢 Dynamic One-Time Password (OTP)**
  Generate time-sensitive, unique passwords that expire after single use, dramatically reducing unauthorized access risks.

- **💾 Robust Database Management**
  Seamlessly integrate user credentials and authentication logs using SQLite's efficient storage mechanism.

## 🗂️ Project Architecture

```
location-and-otp-based-authentication/
│
├── 🌐 api_call/       # API interaction module
├── 🖥️ templates/      # Web interface designs
├── 💾 instance/       # Configuration files
├── 📊 static/         # CSS, JavaScript resources
│
├── 🚀 app.py          # Flask application core
├── 🔐 create_db.py    # Database initialization
└── 📋 requirements.txt # Project dependencies
```

## 🛠️ Quick Setup

### Prerequisites
- Python 3.8+
- pip package manager

### Installation Steps

1. **Clone the Repository**
   ```bash
   git clone https://github.com/ShreyashChilip/location-and-otp-based-authentication.git
   ```

2. **Install Dependencies**
   ```bash
   pip install -r requirements.txt
   ```

3. **Initialize Database**
   ```bash
   python create_db.py
   ```

4. **Launch Application**
   ```bash
   python app.py
   ```

## 🔐 Authentication Workflow

1. User enters credentials
2. System verifies geographic location
3. Generate and send time-limited OTP
4. User completes two-factor authentication

## 📦 Core Dependencies

- **Web Framework**: Flask
- **Database**: SQLite
- **HTTP Requests**: Requests Library
- **Data Handling**: Pandas

## 🏆 Security Principles

- Location-based access control
- Time-sensitive authentication tokens
- Comprehensive logging mechanisms
- Secure API key management

## 📄 Licensing

Released under the **MIT License** 🆓

---

**Developed with ❤️ by Ram Belitkar**
