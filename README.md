# 🏥 Hospital Management System (HMIS)

A comprehensive, web-based **Hospital Management System** built with **PHP** and **MySQL**. This system streamlines hospital operations, patient records, doctor workflows, laboratory tests, pharmacy inventory, accounting, payroll, and administrative management.

---

## ✨ Features & Modules

### 👨‍💼 1. Admin Portal (`/backend/admin`)
* **Patient Management**: Register, update, transfer, and discharge inpatients and outpatients.
* **Employee & Doctor Management**: Add doctors/staff, assign departments, and manage profiles.
* **Pharmacy & Inventory**: Track pharmaceutical categories, inventory levels, vendors, and supplies.
* **Laboratory Management**: Add lab tests, record vitals, and generate lab reports.
* **Surgical & Theatre Records**: Manage surgical procedures and theatre patient queues.
* **Payroll & Accounting**: Generate employee payables, manage accounts receivable, payables, and financial records.
* **Medical Records & Prescriptions**: Access patient histories and medical records.

### 🩺 2. Doctor Portal (`/backend/doc`)
* **Doctor Dashboard**: Quick overview of assigned patients, consultations, and tasks.
* **Patient Care**: Record patient vitals, write lab test requests, and prescribe medications.
* **Lab Results View**: Access laboratory test results and patient vitals.
* **Pharmacy Inventory Lookup**: View current pharmacy stock levels for prescribing.

---

## 🛠️ Tech Stack

* **Language**: PHP (Recommended 7.4 / 8.x, compatible with 5.6+)
* **Database**: MySQL / MariaDB
* **Frontend**: HTML5, CSS3, JavaScript, jQuery, Bootstrap 4
* **UI Plugins**: DataTables, Flatpickr, Footable, Ladda buttons, SweetAlerts

---

## 🚀 Installation & Setup Guide

### 📋 Prerequisites
* Local Web Server (e.g., [XAMPP](https://www.apachefriends.org/), WAMP, or MAMP)
* PHP 7.4 or higher
* MySQL Server & phpMyAdmin

### 🔧 Installation Steps

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/piseshweta6/Hospital-management-system.git
   ```

2. **Move Project Files**:
   Move the `Hospital-management-system` folder to your local server directory:
   * **XAMPP**: `C:/xampp/htdocs/Hospital-management-system`
   * **WAMP**: `C:/wamp64/www/Hospital-management-system`

3. **Import Database**:
   * Open **phpMyAdmin** (`http://localhost/phpmyadmin`).
   * Create a new database named `hmisphp`.
   * Click on **Import**, select `DATABASE FILE/hmisphp.sql`, and click **Go**.

4. **Database Configuration** *(if needed)*:
   Check connection credentials in:
   * `backend/admin/assets/inc/config.php`
   * `backend/doc/assets/inc/config.php`

5. **Run the Application**:
   Open your browser and navigate to:
   * **Landing Page**: `http://localhost/Hospital-management-system/`
   * **Admin Portal**: `http://localhost/Hospital-management-system/backend/admin/`
   * **Doctor Portal**: `http://localhost/Hospital-management-system/backend/doc/`

---

## 🔐 Default Login Credentials

> [!NOTE]
> Demo login details included with the database setup.

| Role | Username / Email | Password |
| :--- | :--- | :--- |
| **Admin** | `admin@mail.com` | `Password@123` |
| **Doctor** | `YDS7L` | `password` |

---

## 📂 Project Directory Structure

```micro-space
Hospital-management-system/
├── DATABASE FILE/
│   └── hmisphp.sql              # MySQL database schema
├── assets/                      # Shared frontend styles, scripts, images
├── backend/
│   ├── admin/                   # Admin portal files & dashboard
│   └── doc/                     # Doctor portal files & dashboard
├── index.php                    # System landing page
├── README.md                    # Project documentation
└── .gitignore                   # Git ignore rules
```

---

## 🤝 Contributing

Contributions, issues, and feature requests are welcome! Feel free to check the [issues page](https://github.com/piseshweta6/Hospital-management-system/issues).

---

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.
