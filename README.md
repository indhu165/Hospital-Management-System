# 🏥 Hospital Management System

A comprehensive Hospital Management System developed using **Python Flask**, **MongoDB**, **HTML**, **CSS**, **JavaScript**, and **Bootstrap**. The system provides role-based access for Users, Doctors, Admins, and Super Admins to efficiently manage hospital operations and appointments.

---

## 📌 Project Overview

The Hospital Management System is designed to streamline hospital operations by providing separate dashboards and functionalities for different user roles. The system enables appointment management, user authentication, doctor management, administrative control, and patient interaction through a user-friendly web interface.

---

## ✨ Features

### 👤 User Module

* User Registration and Login
* User Dashboard
* Book Appointments
* View Appointment Details
* Contact Hospital Administration
* Profile Management

### 👨‍⚕️ Doctor Module

* Doctor Login
* Doctor Dashboard
* View Assigned Appointments
* Manage Patient Information
* Appointment Status Updates

### 🛠️ Admin Module

* Admin Login
* Admin Dashboard
* Manage Doctors
* Manage Users
* Monitor Hospital Activities
* Appointment Management

### 🔐 Super Admin Module

* Super Admin Login
* Super Admin Dashboard
* Manage Administrators
* Full System Access
* Monitor Overall System Performance

### 🌐 General Features

* Responsive User Interface
* Role-Based Authentication
* Secure Login System
* Contact Us Page
* Dynamic Dashboard Statistics
* Appointment Scheduling System

---

## 🛠️ Technologies Used

### Backend

* Python
* Flask

### Database

* MongoDB
* PyMongo

### Frontend

* HTML5
* CSS3
* JavaScript
* Bootstrap

### Additional Libraries

* Flask-Bcrypt
* ReportLab
* QRCode
* Pillow

---

## 📂 Project Structure

```text
Hospital-Management-System/
│
├── modules/
│   ├── admin.py
│   ├── doctor.py
│   ├── user.py
│   ├── superadmin.py
│   ├── db.py
│   ├── login_required.py
│   └── logout.py
│
├── static/
├── templates/
├── app.py
├── requirements.txt
├── README.md
└── vercel.json
```

## ⚙️ Installation

### Clone Repository

```bash
git clone https://github.com/indhu165/Hospital-Management-System.git
cd Hospital-Management-System
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

Windows:

```bash
venv\Scripts\activate
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python app.py
```

---

## 🔑 User Roles

| Role        | Access                           |
| ----------- | -------------------------------- |
| User        | Appointment Booking, Dashboard   |
| Doctor      | Patient & Appointment Management |
| Admin       | Doctor & User Management         |
| Super Admin | Complete System Control          |

---

## 🚀 Future Enhancements

* Online Payment Integration
* Medical Records Management
* Prescription Management
* Email Notifications
* SMS Appointment Alerts
* Advanced Analytics Dashboard

---

## 👨‍💻 Developer

**M. Indhu**

4 th year-Computer Science Engineering

Vidya Jyothi Institute of Technology, Hyderabad

---

## 📄 License

This project is intended for educational and learning purposes.
