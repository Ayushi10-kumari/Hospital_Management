🏥 Hospital Management Database
This repository contains a comprehensive SQL schema for a Hospital Management System, designed to manage patients, doctors, appointments, medical histories, and associated administrative tasks. It provides a foundational database structure for building healthcare applications or hospital ERP systems.

📂 Schema Overview
The SQL file creates the hospital_management schema and defines several interrelated tables:

🔹 Core Tables
patient – Stores patient details including contact and demographic information.

doctor – Contains registered doctors' details.

appointment – Manages appointment scheduling with timestamps and status.

medical_history – Stores past medical records such as conditions, surgeries, and medications.

🔹 Relationship Tables
patient_visits – Links patients to their appointments and symptoms.

patients_history – Maps patients to their historical medical data.

diagnose – Tracks diagnoses and prescriptions by doctors during appointments.

doctor_schedules – Associates doctors with their working schedules.

doctor_view_history – Tracks which doctor viewed which medical history.

🔹 Schedule Table
schedule – Defines daily availability and break timings for doctors.

🛠️ Utility Table
online_retail_app.user_login – A placeholder login table possibly used for authentication.

🚀 How to Use
Import the hospital_management.sql file into your PostgreSQL database.

Run the script to set up the schema and tables.

Integrate with backend logic or hospital software systems.

📌 Notes
Designed with normalized relations and referential integrity using FOREIGN KEY constraints.

Schema can be extended to support billing, room assignments, and more.

📜 License

This project is open-source and available under the MIT License.
