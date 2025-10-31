# 🚗 Vehicle Management System

🎥 **Project Demo Video:** [Watch on YouTube](https://youtu.be/nNSHQSsG4-s)

---

## 📝 Overview
This project is my **final submission for CS50x**, and it represents a simplified version of a **Vehicle Management System** built using **Django** and **SQLite**.  
The purpose of this system is to solve a recurring real-life problem where vehicles are often taken or used **without recording who received them**.  
When that happens, if a vehicle gets a fine, is involved in an accident, or is delayed in returning, there’s no way to know who was responsible.  
This project provides a structured and simple solution to that issue — by ensuring every vehicle transaction is **recorded, traceable, and transparent**.

Unlike large commercial fleet systems, this version focuses only on the **core problem**: vehicle registration and handover, returning vehicles, displaying fines and violations, and transferring vehicles between departments.  
The goal is not to create a complex administrative portal, but rather to demonstrate how a small, well-structured Django project can solve a practical accountability problem in daily operations.

---

## ⚙️ Features

### 1. Vehicle Registration & Handover
Employees can record when they receive a vehicle for inspection rounds or other duties.  
The system logs the **employee’s name, vehicle number, purpose, department, and time of handover**, building a digital record of who used each vehicle.  
This prevents confusion and creates full traceability for every trip.

### 2. Vehicle Return
When an employee **returns from the inspection round**, the return is logged in the system.  
The record is updated to show that the vehicle has been returned and is available again for use.  
This keeps everyone informed about which cars are active, which are idle, and who currently has them.

### 3. Fines and Violations
The system displays all **fines and violations** associated with the vehicles.  
Each record shows the **date, time, and the user who had the vehicle** when the violation occurred.  
This transparency ensures that responsibility is clear, reduces disputes, and promotes careful use of shared resources.

### 4. Vehicle Transfers Between Departments
The system also allows the **transfer of vehicles between departments**.  
Each transfer is logged with the name of the sender, the receiver, and the timestamp.  
This creates an official digital trail for all movements of vehicles, even when different teams or divisions are involved.

---

## 💡 Project Purpose
The main purpose of this project is to **improve accountability** in vehicle usage.  
Without proper records, it’s impossible to track who used which car, when, and for what purpose.  
This often leads to confusion, wasted time, and blame between employees.  

With the **Vehicle Management System**, every action — taking a car, returning it, or transferring it — is recorded digitally.  
If a fine appears, the system can show exactly **who was responsible** at that moment.  
This structure promotes responsibility, discipline, and fair use of vehicles.

Additionally, the system helps avoid conflicts between departments.  
Since all transactions are logged, everyone can verify the data at any time.  
It also serves as a foundation for future improvements such as maintenance tracking, fuel management, and driver performance statistics.

---

## 🧩 Tech Stack
- **Framework:** Django (Python)
- **Database:** SQLite
- **Frontend:** HTML & CSS (custom)
- **Language:** Arabic interface
- **Environment:** CS50 Codespace (Linux-based)

Django was chosen because it provides excellent tools for authentication, database management, and modular development.  
SQLite is ideal for lightweight projects that need a simple, file-based database without external dependencies.  
The front-end design is built entirely with **custom CSS**, providing a simple and responsive interface that I styled manually.  
All labels and pages are fully localized in Arabic to make the system easy to use for Arabic-speaking users.

---

## 🧠 What I Learned
During development, I learned how to:
- Structure a Django project with multiple apps, templates, and static files.  
- Use models and migrations to create a reliable database schema.  
- Manage authentication and session-based access for users.  
- Build dynamic forms that interact with the database in real time.  
- Handle Arabic text correctly inside Django forms and templates.  
- Design and style the interface using **pure CSS**, focusing on clarity, simplicity, and responsive layout without relying on external frameworks.  
- Apply real-world thinking to software design — understanding that solving a small but real problem is often more valuable than building something big with no clear use case.

This project gave me practical experience with both backend and frontend logic, debugging, and working efficiently inside **CS50 Codespace**.  
It also improved my problem-solving skills and my ability to translate a real-world issue into a working digital solution.

---

## ▶️ How to Run Locally (in CS50 Codespace or any machine)
To run this project locally, follow these simple steps:

1. Open your **terminal** and navigate to your project folder:  
   ```bash
   cd vehicle-management
