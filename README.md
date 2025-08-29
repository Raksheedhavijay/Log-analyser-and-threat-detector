#  Java Log Analyzer & Threat Detector

##  Project Title
**Java Log Analyzer & Threat Detector**

##  Project Description
A console-based Java application that parses server logs (e.g., Apache, SSH) and detects suspicious activities such as brute-force login attempts, SQL injection, and path traversal attacks. The system leverages **Object-Oriented Programming (OOP)** concepts for modular design and scalability.

---

##  Problem Statement
In modern server environments, administrators face challenges in identifying **unauthorized access attempts** and **malicious activities** hidden within large log files.  
This project aims to provide a **lightweight Java-based tool** to detect threats automatically and generate actionable insights.

---

##  Target Users
- **System Administrators** – to monitor server activity.  
- **Security Analysts** – for early detection of potential intrusions.  
- **Developers/Students** – as a learning project in cybersecurity and Java OOP design.

---

##  OOP Concepts Used
- **Encapsulation** → Each class bundles data and methods (e.g., `LogEntry`).  
- **Abstraction** → Hides complexity of parsing & detection (`LogParser`, `ThreatDetector`).  
- **Inheritance** → `ThreatDetector` is extended by `BruteForceDetector`, `SQLInjectionDetector`, etc.  
- **Polymorphism** → Multiple detectors implement `detect()` differently.  
- **Composition** → `Analyzer` uses `LogParser`, `ThreatDetector`, and `Exporter` together.  
- **Exception Handling** → Custom exceptions (`InvalidLogFormatException`) ensure robustness.

---

##  Features
- Parse server logs efficiently.  
- Detect brute-force, SQL injection, and path traversal attempts.  
- Store suspicious IPs into a blocklist file.  
- Modular OOP-based design for extensibility.  

---

##  Advantages
- Lightweight and **pure Java** (no external dependencies).  
- Demonstrates strong **OOP principles**.  
- Useful for **real-world security monitoring**.  
- Extensible: new threat detectors can be added easily.  

---

