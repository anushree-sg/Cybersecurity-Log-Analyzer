# 🛡️ Cybersecurity Log Analyzer

[![Java](https://img.shields.io/badge/Language-Java-orange.svg)](https://www.java.com/)
[![Database](https://img.shields.io/badge/Database-MySQL-blue.svg)](https://www.mysql.com/)
[![Architecture](https://img.shields.io/badge/Architecture-Layered-green.svg)](#)

[cite_start]A robust, menu-driven command-line application designed to simulate a **Security Operations Center (SOC)** logging system[cite: 5, 6]. [cite_start]This tool records and analyzes security-related events to identify suspicious activities in real-time[cite: 6].

---

## 📖 Project Overview
[cite_start]The **Cybersecurity Log Analyzer** bridges the gap between core backend development and cybersecurity principles[cite: 11, 40]. [cite_start]It demonstrates how to handle sensitive security data using industry-standard practices[cite: 40].

### 🎯 Key Objectives
* [cite_start]**Database Integration**: Master JDBC and MySQL connectivity[cite: 8].
* [cite_start]**Data Management**: Implement full CRUD operations for security logs[cite: 9].
* [cite_start]**Structural Integrity**: Apply a layered software architecture for scalability[cite: 10].
* [cite_start]**Cyber Simulation**: Model real-world security event logging[cite: 11].

---

## 🛠️ Tech Stack
| Component | Technology | Role |
| :--- | :--- | :--- |
| **Language** | Core Java | [cite_start]Application logic [cite: 13] |
| **Driver** | JDBC | [cite_start]Database connectivity [cite: 14] |
| **Storage** | MySQL | [cite_start]Persistent data storage [cite: 15] |
| **Interface** | CLI | [cite_start]User interaction [cite: 16] |

---

## 📂 System Architecture & Design
[cite_start]The application follows a **Layered Architecture** to ensure a clean separation of concerns between the user interface, business logic, and data access[cite: 10, 33].

### Database Schema
[cite_start]The system operates on a database named `cyberdb` with a dedicated table for event history[cite: 18].



---

## 🚀 Functional Modules
* [cite_start]✅ **Add Security Log**: Register new security events manually[cite: 20].
* [cite_start]🔍 **View Log by ID**: Targeted retrieval of specific log entries[cite: 21].
* [cite_start]📋 **View All Logs**: Comprehensive audit of all recorded activities[cite: 22].
* [cite_start]⚠️ **Failed Login Tracker**: Specialized view for monitoring unauthorized access attempts[cite: 23].
* [cite_start]🗑️ **Log Management**: Securely delete obsolete records[cite: 24].

---

## 🔒 Security Best Practices
Security is baked into the development process:
* [cite_start]**SQLi Protection**: Implementation of `PreparedStatement` to neutralize SQL Injection threats[cite: 26].
* [cite_start]**Validation**: Robust input validation within the Service layer[cite: 27].
* [cite_start]**Layer Separation**: Strict boundaries between application layers to prevent data leaks[cite: 28].

---

## 🔮 Future Roadmap
- [ ] [cite_start]**User Auth**: Add a secure login system for the analyzer[cite: 35].
- [ ] [cite_start]**Encryption**: Implement password hashing (e.g., BCrypt)[cite: 36].
- [ ] [cite_start]**Heuristics**: Add Brute-force attack detection logic[cite: 37].
- [ ] [cite_start]**Reporting**: Automated generation of security audit reports[cite: 38].

---

## 🎓 Learning Outcomes
* [cite_start]Practical experience with JDBC and relational database design[cite: 30, 31].
* [cite_start]Deepened understanding of cybersecurity event logging concepts[cite: 32].
* [cite_start]Proficiency in building layered, maintainable Java applications[cite: 33].
