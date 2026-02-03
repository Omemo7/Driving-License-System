# DVLD (Driving & Vehicle License Department) System 🚗

A comprehensive, enterprise-grade desktop application designed to automate the management of driving licenses, tests, and traffic operations. This system manages the complete lifecycle of a driver, from the initial learner's permit to testing, licensing, and international permit issuance.

## 🏗 System Architecture

The solution implements a strict **3-Tier (N-Tier) Architecture** to ensure scalability, maintainability, and security:

* **Presentation Layer:** Provides a rich, responsive Windows Forms user interface for clerks and administrators to perform daily operations.
* **Business Logic Layer (BLL):** Encapsulates the complex validation rules, calculations, and workflow logic for license eligibility and test scheduling.
* **Data Access Layer (DAL):** Handles all database interactions, executing optimized stored procedures and queries against the SQL Server database.

## 🚀 Key Modules & Features

### 🪪 License Management
* **Issuance Lifecycle:** Complete workflows for issuing Local, International, and Replacement licenses.
* **Administrative Actions:** Capabilities to Renew expired licenses, Replace lost or damaged cards, and Detain/Release licenses based on traffic violations and fines.
* **Driver History:** Centralized tracking of a driver's entire history, including active licenses, past cancellations, and violation records.

### 📝 Testing & Appointments
* **Scheduling System:** Robust logic to book appointments for Vision, Theory, and Practical driving tests, ensuring no scheduling conflicts.
* **Test Results:** Workflow to record pass/fail results that automatically trigger the next stage of the application process.
* **Retake Logic:** Rules handling failing candidates, including locking retakes for a specific duration and applying penalty fees.

### 👥 People & User Administration
* **Centralized Person Profile:** A unified module to manage demographic data, ensuring a single source of truth for all applicants and employees.
* **RBAC (Role-Based Access Control):** Secure login and user management system that restricts sensitive administrative operations to authorized personnel only.

### 🌍 Application Processing
* **Service Requests:** Handling mechanism for various application types (New Local License, Renew License, Replacement) with unique validation rules for each.
* **Fee Management:** Automated calculation of application fees based on the specific service type and applicant status.

## 🛠 Tech Stack

* **Language:** C#
* **Framework:** .NET Framework (Windows Forms)
* **Database:** MS SQL Server
* **Architecture:** 3-Tier (Presentation, BLL, DAL)
* **Data Access:** ADO.NET

## 📸 System Screenshots

| Main Dashboard | License Info | Test Appointment |
|:---:|:---:|:---:|
| <img src="" width="250" alt="Dashboard"> | <img src="" width="250" alt="License Card"> | <img src="" width="250" alt="Scheduling"> |
| *Admin Dashboard* | *Driver License* | *Test Booking* |
