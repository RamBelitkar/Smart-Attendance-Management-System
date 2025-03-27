# 🎓 Smart Attendance Management System

## 🌟 Project Overview

A comprehensive Flask-based web application designed to streamline attendance tracking for educational institutions, featuring advanced location verification, OTP-based authentication, and real-time attendance marking.

## ✨ Key Features

### 🔐 Authentication
- Secure login system with role-based access control
- User authentication using Flask-Login
- Password encryption with Flask-Bcrypt

### 📍 Location Verification
- Geolocation-based attendance marking
- Ensures students are within campus premises
- Uses geodesic distance calculation

### 🔢 OTP Verification
- One-Time Password (OTP) generation
- Email and SMS-based OTP delivery
- Time-limited OTP validation

### 📊 Attendance Tracking
- Support for lecture and practical batch attendance
- Real-time attendance record generation
- Comprehensive attendance views for students and administrators

## 🛠 Tech Stack

- **Backend**: Flask
- **Database**: SQLAlchemy with SQLite
- **Authentication**: Flask-Login, Flask-Bcrypt
- **Email**: Flask-Mail
- **SMS**: Twilio
- **Geolocation**: GeoPy

## 🚀 Installation

### Prerequisites
- Python 3.8+
- pip

### Setup Steps
```bash
# Clone the repository
git clone https://github.com/your-username/attendance-management-system.git

# Navigate to project directory
cd attendance-management-system

# Create virtual environment
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt

# Initialize database
flask db upgrade

# Run the application
flask run
```

## 📋 Configuration

1. Configure `keys.py` with:
   - Twilio credentials
   - SMTP email settings
   - Location coordinates

2. Set environment variables for sensitive information

## 🔒 Security Features

- Location verification within 50 meters of campus
- OTP-based attendance marking
- Role-based access control
- Secure password hashing
- Session management

## 📱 Modules

- **User Authentication**
- **Location Verification**
- **OTP Generation**
- **Attendance Marking**
- **Attendance Reporting**


**Made with ❤️ & 🐍 Python-Flask**
