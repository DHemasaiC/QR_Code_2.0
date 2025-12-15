# QR Code Ownership Tracking System

A Python-based web application to manage and track device ownership transfers using QR codes.  
Designed with a focus on **clean backend logic, data validation, and testable code**.

## 📌 Overview
This project enables organizations to:
- Track current ownership of devices
- Log historical ownership transfers
- Prevent invalid or duplicate ownership resets
- Access device data via QR codes

Built as a production-style backend application emphasizing **Python engineering practices** rather than UI.

---

## 🛠 Tech Stack
- **Python 3**
- **Flask**
- CSV-based persistence (lightweight data store)
- QR Code generation
- HTML/Jinja templates
- Git-based version control

---

## ✨ Key Features
- QR-code–based device identification
- Ownership transfer with validation
- Immutable device history logging
- Owner reset logic with safeguard checks
- Timestamped history records (IST)
- Input validation for PS Number, phone, and email

---

## 🧠 Engineering Highlights
- Clear separation of business logic and routing
- Defensive input validation to prevent invalid state
- Idempotent reset operation (`Already under the owner`)
- Structured data logging for auditability
- Designed for easy extension to DB-backed storage

---

## 📂 Project Structure

QR_Code_2.0
- app.py # Flask application entry point
- device_data.csv # Current device ownership data
- device_history.csv # Historical ownership log
- templates/ # HTML templates
- static/ # Static assets
- README.md # Project documentation