
# 🧰 System Maintenance Suite – Bash Scripting Project

## 🧾 Overview
This project is a **Bash-based System Maintenance Suite** designed to automate essential Linux system maintenance tasks.  
It includes scripts for:

- File and directory backup
- System update and cleanup
- Log monitoring and alert capture
- Centralized logging of all operations
- A menu-driven interface for easy use

All scripts can be used individually or accessed through the **main menu (`MENU.sh`)**.

---

## 💻 Supported Platforms
- Ubuntu / Debian Linux
- Kali Linux
- Linux server systems
- Windows (via **WSL — Ubuntu Terminal**)

---

## ⚙️ Setting Up Ubuntu Terminal on Windows (WSL)

### 1️⃣ Open Command Prompt as Administrator
Press **Windows + S**, type **cmd**  
Right-click → **Run as Administrator**

### 2️⃣ Enable WSL and Install Ubuntu
```bash
wsl --install

3️⃣ Restart When Prompted

4️⃣ Create Linux Username and Password After Setup



---

📁 Project Structure

BASH_SUITE/
│
├── BACKUP.sh
├── CONFIG.sh
├── LOG_MONITOR.sh
├── UPDATE_CLEANUP.sh
├── MENU.sh
└── logs/
    └── maintenance.log

File/Folder	Purpose

BACKUP.sh	Creates timestamped backups from source directory to backup directory.
UPDATE_CLEANUP.sh	Updates system packages and cleans cache to free disk space.
LOG_MONITOR.sh	Scans /var/log for errors and warnings and records findings.
CONFIG.sh	Stores configurable variables used by other scripts.
MENU.sh	Main interactive script providing a menu to access all tools.
logs/maintenance.log	Master log file that stores all operations, alerts, and errors.



---

🖥️ How to Run the Suite

1️⃣ Open Terminal

ctrl + alt + t

2️⃣ Navigate to the Project Directory

cd WIPRO_CAPSTONE-PROJECT/BASH_SUITE

3️⃣ Give Execute Permission

chmod +x *.sh

4️⃣ Run the Menu Interface

./MENU.sh

You will see:

==============================
   SYSTEM MAINTENANCE SUITE
==============================
1) Run Backup
2) Update & Clean System
3) Monitor Logs
4) View Log File
5) Exit


---

🧾 Log File Details

All operations performed using the scripts are recorded in:

BASH_SUITE/logs/maintenance.log

This includes:

Time of execution

Actions performed

Errors detected

System warnings


Purpose: Helps in auditing, debugging, and verifying tasks during project presentation.


---

🌟 Features

✅ Menu-driven interface for easy navigation

✅ Automated backup and maintenance scripts

✅ Real-time log scanning and alert recording

✅ Central logging for all operations

✅ Works in both Linux and WSL environments



---

👨‍💻 Author

Sanoj Shreyas Deo 
B.Tech CSE – Siksha ’O’ Anusandhan University
WIPRO Capstone Project


