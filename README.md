# 🚗 DVLD – Driving License Management System

## 📌 Project Overview
DVLD (Driving & Vehicle License Department) is a desktop management system that simulates a real-world government driving license administration workflow.

The system manages people, users, applications, tests, licenses, and drivers using a clean **3-Tier Architecture** with a structured SQL database.

This project was built to practice real enterprise-level development concepts such as layered architecture, user controls, delegation, events, and database-driven workflows.

---

##  Key Concepts & Lessons Applied
- 3-Tier Architecture (DAL / BLL / UI)
- User Controls & reusable components
- Exposing properties in User Controls
- Sending data between forms
- Delegates & events with parameters
- Clean separation of concerns
- Real-world business logic implementation

---

##  Tech Stack

### Application
- C# (.NET Framework)
- Windows Forms (WinForms)

### Architecture
- Data Access Layer (DAL)
- Business Logic Layer (BLL)
- Presentation Layer (UI)

### Database
- SQL Server
- Relational Database Design
- Stored procedures & queries

---

##  Database Structure
- People & Countries
- Users & Authentication
- Applications & Application Types
- Local & International Driving License Applications
- Test Types & Test Appointments
- Tests
- Drivers & Licenses
- License Renewal & Replacement
- Detained & Released Licenses

---

##  Main Features

###  People Management
- Add / Update / Find people
- Person card & filtering controls
- Image handling
- Person history tracking

###  Users Management
- User accounts
- Login system
- Change password
- Role-based access

###  Applications Management
- Local Driving License Application
- International Driving License Application
- Renew License
- Replace Lost or Damaged License

###  Tests Management
- Schedule tests
- Take tests
- Retake failed tests
- Test appoint
