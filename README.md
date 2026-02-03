# DVLD (Driving & Vehicle License Department) System 🚗

A comprehensive, enterprise-grade desktop application designed to automate the management of driving licenses, tests, and traffic operations. This system manages the complete lifecycle of a driver, from the initial learner's permit to testing, licensing, and international permit issuance.

## 🏗 System Architecture

The solution implements a strict **3-Tier (N-Tier) Architecture** to ensure scalability, maintainability, and security:

* **Presentation Layer (Windows Forms):** Provides a rich, responsive user interface for clerks and administrators.
* **Business Logic Layer (BLL):** Contains the complex rules for license eligibility, test scheduling, and fee calculations (e.g., `clsLicense`, `clsTest`).
* **Data Access Layer (DAL):** Handles all communication with the **SQL Server** database, executing stored procedures and queries.

## 🚀 Key Modules & Features

### 🪪 License Management
* **Issuance Lifecycle:** Workflows for issuing Local and **International Licenses**.
* **Administrative Actions:** Capabilities to Renew, Replace (Lost/Damaged), and Detain/Release licenses based on traffic violations.
* **Driver History:** Comprehensive tracking of a driver's license history and active status.

### 📝 Testing & Appointments
* **Scheduling System:** Logic to book appointments for Vision, Theory, and Practical driving tests.
* **Test Results:** Workflow to record pass/fail results and automatically update application status.
* **Retake Logic:** Rules handling failing candidates and locking retakes without fees.

### 👥 People & User Administration
* **Centralized Person Profile:** A unified module (`clsPerson`) to manage demographic data, ensuring no duplication of records across the system.
* **RBAC (Role-Based Access Control):** Secure login and user management (`clsUser`) to restrict sensitive operations to authorized personnel.

### 🌍 Application Processing
* **Service Requests:** Handling different application types (New Local License, Renew License, Replacement).
* **Fee Management:** Automated calculation of application fees based on service type.

## 🛠 Tech Stack

* **Language:** C#
* **Framework:** .NET Framework (Windows Forms)
* **Database:** MS SQL Server
* **Architecture:** 3-Tier (Presentation, BLL, DAL)
* **Data Access:** ADO.NET

