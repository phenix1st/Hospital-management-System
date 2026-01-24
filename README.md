# Hospital Management System (HMS)

A **web-based Hospital Management System** built with **Django**, designed to efficiently manage hospital operations. The system provides **role-based dashboards** for **Admin**, **Doctors**, and **Patients**, enabling seamless management of patient records, appointments, and hospital workflows.  

---

## Table of Contents

- [Overview](#overview)  
- [Features](#features)  
- [User Dashboards](#user-dashboards)  
- [Tech Stack](#tech-stack)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Screenshots](#screenshots)  
- [License](#license)  

---

## Overview

This project is a complete **Hospital Management System** that streamlines hospital operations. It ensures role-based access and functionality:

- **Admins** manage doctors, patients, and appointments.  
- **Doctors** manage assigned patients, appointments, and access discharge records.  
- **Patients** manage appointments, view assigned doctors, and access discharge information.  

The system uses **Django**, **Bootstrap**, and **xhtml2pdf** for PDF generation of bills.

---

## Features

### Admin Features:
- Add, update, delete doctors and patients.  
- Approve or reject doctor and patient accounts.  
- View and manage appointments.  
- Discharge patients and generate final bills in PDF format.  
- Dashboard overview with total counts of doctors, patients, and appointments.  

### Doctor Features:
- View assigned patients and patient details.  
- Approve, reject, or delete appointments.  
- Access discharge records of patients.  
- Search patients by name or symptoms.  
- Dashboard overview with patient and appointment statistics.  

### Patient Features:
- Book appointments with doctors.  
- View upcoming and past appointments.  
- Access discharge details and bills if admitted.  
- Search and view doctors by specialization.  
- Dashboard overview with doctor information and appointment status.  

---

## User Dashboards

### Admin Dashboard
- Central hub for hospital management.  
- Overview cards: total doctors, patients, and appointments.  
- Quick access to add, update, or delete doctors and patients.  
- Approve or reject pending doctors/patients.  
- Discharge patients and generate bills.  

### Doctor Dashboard
- Overview of assigned patients, appointments, and discharged patients.  
- Manage patient details and appointments.  
- Search patients by name or symptoms.  
- Sidebar navigation for profile, patients, and appointments.  

### Patient Dashboard
- View personal information and assigned doctor details.  
- Book and view appointments.  
- Access discharge records and bills.  
- Search doctors by department or name.  

---

## Tech Stack

- **Backend:** Django (Python)  
- **Frontend:** HTML, CSS, Bootstrap 4/5, JavaScript  
- **Database:** SQLite (default) / PostgreSQL (optional)  
- **PDF Generation:** xhtml2pdf  
- **Email:** Django Email backend  

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/hospital-management-system.git
