# 🏥 Relivox – Medical Voice Memo & Patient Record System

## 📌 Overview

Relivox is a database-driven web application designed to streamline clinical documentation by integrating:

* Voice recordings
* Automated transcription
* Structured medical reports

The system provides a centralized, secure, and efficient platform for managing patient records and clinical workflows.

---

## 🚀 Features

* 🎤 Voice recording management
* 📝 Transcription storage and processing
* 📄 Medical report generation (Progress & Nurse notes)
* 👩‍⚕️ User roles (Doctor & Admin)
* 🔐 Secure patient data handling
* 📊 Audit logging for all system activities
* ⚡ Optimized database with indexing & normalization
* 🔄 CRUD operations for all entities

---

## 🧱 Tech Stack

* **Frontend:** PHP, HTML, CSS
* **Backend:** MySQL
* **Server:** Rowan University Elvis Server
* **Tools:** MySQL Workbench

---

## 🗄️ Database Design

The system follows strong database principles:

* Normalization (1NF, 2NF, 3NF)
* Referential Integrity
* Indexed queries for performance
* Use of:

  * Views
  * Stored Procedures
  * Functions
  * Triggers

### Core Entities:

* User
* Patient
* Recording
* Transcription
* Report
* Template
* AuditLog
* EmailLog

---

## 🔄 Workflow

1. Doctor records patient voice notes
2. Recording is stored in database
3. Transcription is generated
4. Reports are created from transcription
5. Reports are stored and optionally emailed
6. All actions are logged for auditing

---

## 📷 System Modules

* User Management
* Patient Management
* Reports & Transcriptions
* Views & Analytics
* Stored Procedures Execution
* Audit Logs Tracking

---

## 🌐 Live Demo

🔗 http://elvis.rowan.edu/~pateld28/AdvanceDatabase/Project/code.php

---

## 🎯 Objectives

* Improve clinical documentation efficiency
* Reduce transcription errors
* Maintain secure and structured patient records
* Provide scalable healthcare data solution

---

## 🔒 Security Features

* Role-based access control
* Data encryption (sensitive fields)
* Audit logging for all changes
* Backup support

---

## 📈 Future Enhancements

* Integration with speech-to-text APIs
* Mobile application support
* EHR system integration (FHIR standard)
* Advanced analytics dashboard

---

## 👩‍💻 Author

**Disha Patel**

---

## 📜 License

This project is for academic purposes.
