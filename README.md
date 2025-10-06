# MediLink – Digital Health Management System

**MediLink** is a HealthTech platform that connects patients, doctors, and healthcare facilities on a single cloud-based system.  
It provides tools for managing hospital appointments, patient medical records, and teleconsultations while ensuring data security and compliance.

---

### ⚕️ Core Features
- Patient registration and secure login  
- Doctor–patient appointment scheduling  
- Electronic medical record (EMR) storage  
- Real-time chat and teleconsultation  
- Prescription generation and uploads  
- Admin dashboard for hospital management  
- Notifications via SMS and Email  

---

### 🧠 Tech Stack
| Layer | Technology |
|-------|-------------|
| **Frontend (Mobile + Web)** | Flutter |
| **Backend API** | Python (FastAPI) |
| **Database** | PostgreSQL (ReinHost Cloud DB) |
| **Hosting** | ReinHost VPS / cPanel |
| **Notifications** | SendGrid (Email), Twilio (SMS) |
| **Storage** | ReinHost Encrypted File Storage |

---

### 🧩 System Architecture

Patients & Doctors → Flutter Web/Mobile App
│
│──> FastAPI Backend (ReinHost VPS)
│
│──> PostgreSQL Database (ReinHost Cloud DB)
│
│──> SendGrid / Twilio for notifications
│
└──> Encrypted file storage for medical records


---

### 🔒 Security & Compliance
- End-to-end encrypted communication  
- Role-based authentication (Patient, Doctor, Admin)  
- Encrypted medical record storage  
- GDPR & HIPAA-aligned data protection policies  

---

### 🧾 Status
**Concept build for portfolio demonstration.**  
MediLink showcases full-stack capability in building healthcare solutions with secure cloud integration and patient data management.

---

### 👨🏽‍💻 Developer
**James Friday**  
📧 jamesfriday007@gmail.com  
🌐 GitHub: [https://github.com/CityRock007](https://github.com/CityRock007)
