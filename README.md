# med---Farm-platform-2nd-year-Project
A multi-platform healthcare project including Doctor &amp; Pharmacy web portals and a Patient mobile app for electronic prescriptions and rare medication availability with map integration.

# Electronic Prescription & Medication Locator System

## Overview
This project is a healthcare solution that connects **doctors, patients, and pharmacies** through an electronic prescription system.  
It helps patients **locate pharmacies that have prescribed medications**, especially **rare medicaments**, using real-time data and map integration.

The project includes:
- A **Doctor Website**
- A **Pharmacy Website**
- A **Patient Mobile Application**

Developed as an academic project in 2024.

---

## Problem Statement
Patients often struggle to find pharmacies that have specific or rare medications in stock.  
Doctors also need a faster and more reliable way to send prescriptions digitally.

This system solves both problems by enabling **electronic prescriptions** and **medication availability search with location mapping**.

---

## System Components

### 👨‍⚕️ Doctor Web Application
- Doctor authentication
- Create and send **electronic prescriptions**
- View patient history
- Select medications from a centralized database

### 🏪 Pharmacy Web Application
- Pharmacy authentication
- Manage medication inventory
- Update availability of medicines
- Receive electronic prescriptions

### 📱 Patient Mobile Application
- Receive electronic prescriptions
- View full medication details
- Search pharmacies that have the prescribed medicine
- Locate pharmacies on a **map**
- Especially useful for **rare medications**

---

## Key Features
- Electronic prescription (e-Prescription)
- Centralized medication database
- Rare medication availability tracking
- Pharmacy location using maps
- Multi-platform system (Web + Mobile)
- Secure user authentication

---

## Tech Stack


### Frontend
- HTML / CSS / JavaScript  
- React / Node / Vue

### Backend
- Node.js
- REST APIs

### Mobile App
- Android (Kotlin)  
- Flutter 

### Database
- MongoDB

### Other
- Maps API (Google Maps / OpenStreetMap)
- Git & GitHub

---

## Architecture
- Doctor and Pharmacy platforms communicate with a centralized backend
- Patient app fetches prescription and pharmacy data via APIs
- Map integration used to display nearby pharmacies

---

## How to Run the Project
```bash
# Backend
npm install
npm start

# Frontend
npm install
npm start

