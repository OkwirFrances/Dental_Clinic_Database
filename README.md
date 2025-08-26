
# 🦷 Dental Clinic Database (MySQL)

This project is a **MySQL relational database** designed for managing the operations of a dental clinic.  
It provides a structured way to store and manage data about patients, dentists, appointments, treatments, and invoices.

---

## 📌 Features
- Store patient records (personal details, contact information, medical history).
- Manage dentist details (specialization, department).
- Track appointments (date, time, patient, dentist).
- Record treatments given during appointments.
- Generate invoices linked to appointments and patients.
- Ensure data integrity with relationships and constraints.

---

## 🗂 Database Schema

**Entities:**
- **Patients**
- **Dentists**
- **Appointments**
- **Treatments**
- **Invoices**

**Relationships:**
- Patients ↔ Appointments (one-to-many)
- Dentists ↔ Appointments (one-to-many)
- Appointments ↔ Treatments (one-to-many)
- Payments ↔ Invoices (one-to-many)
- Appointments ↔ Invoices (one-to-one)

---

## ⚙️ Installation & Setup

### 1. Clone the repository
```bash
git clone https://github.com/yourusername/dental_clinic_database.git
cd dental_clinic_database
