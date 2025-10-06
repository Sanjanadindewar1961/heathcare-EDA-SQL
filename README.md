# 🏥 HealthDB – Healthcare Management System (SQL Project)

**HealthDB** is a structured SQL-based healthcare database designed to simulate the operations of a medical facility. It manages key components such as patient records, doctor information, appointments, prescriptions, and billing processes. The database allows users to perform data analysis, track financial metrics, and support clinical decision-making.

---

## 📌 Project Objectives

- Design a relational database tailored to a healthcare environment.
- Store and manage data related to patients, doctors, visits, payments, and medications.
- Analyze patient behavior, doctor performance, and financial trends.
- Provide insights for operational efficiency and clinical care improvement.

---

## 🗂️ Database Overview

The database is composed of five core entities:

### 1. **Patients**
Captures demographic information such as:
- Full name
- Date of birth
- Gender
- Unique patient ID

### 2. **Doctors**
Stores data on medical professionals, including:
- Full name
- Specialty
- Unique doctor ID

### 3. **Appointments**
Links patients to doctors and includes:
- Appointment date
- Reason for visit
- Foreign keys referencing patients and doctors

### 4. **Billing**
Represents financial transactions, including:
- Amount charged
- Payment status (Paid, Pending)
- Payment date
- Appointment linkage

### 5. **Prescriptions**
Documents prescribed medications:
- Medication name
- Dosage
- Instructions
- Related appointment ID

---

## 🔄 Data Relationships

- **One-to-Many**: A patient can have multiple appointments.
- **One-to-Many**: A doctor can attend multiple appointments.
- **One-to-One**: Each appointment can have a corresponding billing entry.
- **One-to-Many**: Each appointment may result in multiple prescriptions.

---

## ⚙️ Key Functionalities

- Track patient visit history and medical prescriptions.
- Analyze doctor workload and specialization trends.
- Monitor billing status and generate financial summaries.
- Assess appointment frequencies and identify gaps in patient care.
- Identify the most commonly prescribed medications and their dosages.
- Report on gender distribution and demographic statistics.

---

## 📈 Potential Use Cases

- **Clinical Insights**: Track frequent patient complaints, prescription patterns, and treatment history.
- **Financial Reporting**: Identify total billed amounts, pending payments, and revenue per doctor or department.
- **Operational Management**: Evaluate doctor performance and appointment volumes by date, specialty, or patient demographics.
- **Health Analytics**: Support public health studies using aggregated and anonymized patient data trends.

---

## 💻 Technologies Used

- **Database**: MySQL
- **Language**: SQL (Structured Query Language)
- **Tools**: MySQL Workbench / CLI

---

## 🚀 Getting Started

1. Set up a MySQL environment.
2. Create the database and import the schema (`healthdb.sql`).
3. Use the predefined structure to perform various analytical and operational tasks.

---

## 📬 Feedback & Contributions

If you find this project useful or would like to contribute (e.g., with better indexing, data normalization, or advanced queries), feel free to fork the repository or open an issue.

---

## 📜 License

This project is provided for educational and demonstration purposes. You may modify or distribute it with appropriate credit.

