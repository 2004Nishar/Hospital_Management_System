# 🏥 Hospital Management System

A web-based Hospital Management System built with **Flask**, **SQLite3**, **Tailwind CSS**, and **JavaScript** to help manage hospital workflows including appointments, patients, medical records, and prescriptions.

---

## 📌 Features

### 🔐 Authentication
- Role-based login system (Doctor, Patient)

### 🩺 Doctor Dashboard
- View patient list
- Manage appointments
- Add/view medical records
- Write/view prescriptions
- Manage profile

### 👨‍⚕️ Patient Dashboard
- Book appointments
- View medical history and prescriptions
- Browse doctors
- Update profile and settings

---

## 📁 Project Structure
#### Hospital-Management-System/
- │
- ├── app.py # Main Flask app
- ├── database.py # DB connection logic
- ├── patient.py # Patient DB logic
- ├── prescription.py # Prescription DB logic
- ├── *.db # SQLite database files
- │
- ├── templates/ # HTML templates
- │ ├── Login/
- │ ├── Doctor/
- │ └── Patient/
- │
- ├── static/ # Static files
- │ ├── styles.css
- │ ├── script.js
- │ └── images/
- │
- ├── requirements.txt # Python dependencies


---

## ⚙️ How to Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/your-username/hospital-management-system.git
cd hospital-management-system
```
```bash
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
```
```bash
pip install -r requirements.txt
```
```bash
python app.py
```
```bash
http://127.0.0.1:5000
```
---
## 📸 Screenshots
### 👨‍⚕️ Doctor Dashboard
![Doctor Dashboard](Screenshots/Doctor_dashboard.png)

### 🧑‍⚕️ Patient Dashboard
![Patient Dashboard](Screenshots/Patient_Dashboard.png)

---

## 📦 Requirements
```bash
Flask==2.3.3
gunicorn==21.2.0
```
- SQLite3 is part of the Python Standard Library, so you don’t need to install it separately.
---
## 🙋‍♂️ Author
***Nishar Chavan***
- Feel free to contribute, raise issues, or fork the project.
---
