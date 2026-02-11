# ActivCare Web-Based Electronic Medical Record (EMR) System

## 📌 Project Overview

The *ActivCare Web-Based Electronic Medical Record (EMR) System* is a role-based healthcare management platform developed for ActivCare Home Health Solution.

This system centralizes patient records, inquiry processing, scheduling coordination, and report generation into a unified digital platform. It replaces manual documentation previously handled through Microsoft Excel and Google Sheets, reducing redundancy, minimizing errors, and improving workflow efficiency.

The platform promotes structured data management, real-time coordination among healthcare providers, and streamlined operations tailored for home health services.

---

## 🎯 Objectives

- To Design and implement a module to manage Patient Records
- To Design and implement an account management module that organize user roles
- To design and implement a Staff Scheduling module
- To Design and implement a Patient Chart Module and tracks the Service given to patients
- To design a module that will generate timely report

---

## 👥 User Roles & Access Control

The system supports four primary roles:

### 🔐 Admin
- Manage user accounts
- Oversee system records
- Monitor inquiries and reports

### 👨‍⚕️ Doctor
- View assigned patients
- Access medical charts
- Provide medical notes and updates

### 🩺 Nurse Case Manager (NCM)
- Manage patient inquiries
- Filter and track inquiry status
- Coordinate patient care
- Update patient records

### 👩‍⚕️ Caregiver
- View assigned patients
- Access care instructions
- Update care logs

Each role is protected by a session-based authentication system with controlled dashboard redirection.

---

## 🚀 Core Features

### ✅ Role-Based Login System
- Secure POST authentication
- PHP session management
- Automatic dashboard redirection per role

### 📋 Inquiry Management Module
- Date range filtering
- Status dropdown filtering
- Patient/contact search
- Organized and structured inquiry tracking

### 🗂 Patient Chart Management
- Patient information storage
- Medical history tracking
- Care notes documentation

### 📊 Report Generation
- Structured report view
- Role-based access restrictions
- Printable format support

---

## 🛠 Technologies Used

- PHP (Backend)
- MySQL (Database)
- HTML5
- CSS3
- JavaScript
- Bootstrap
- XAMPP (Local Development Environment)

---

## ⚙️ Installation Guide (Local Setup)

1. Install XAMPP.
2. Clone or download this repository.
3. Place the project folder inside:
   
   xampp/htdocs/
   
4. Open phpMyAdmin and create a new database.
5. Import the provided .sql database file.
6. Configure database credentials inside:
   
   config.php
   
7. Start Apache and MySQL from XAMPP.
8. Access the system via:
   
   http://localhost/project-folder-name
   

---

## 🔒 Security Features

- Session-based authentication
- Role-restricted dashboards
- Controlled access to patient data
- Structured database relationship design

---

## 🏥 Client Information

Developed for:
*ActivCare Home Health Solution*

Services include:
- Palliative homecare
- 1:1 caregiver-to-patient care
- Teleconsultation services
- In-house pharmacy coordination

---


## 📅 Project Status

Prototype → Functional Web-Based EMR System  
Currently under refinement and feature optimization.

---

## 👨‍💻 Developers

- [Russel Rome Soriano]
- [Alexis Tolenada Passion]
- [Yvonne Chloe Domingo]
- [Jerwin Pobre]

---

## 📄 License

This project was developed for academic and institutional purposes.
