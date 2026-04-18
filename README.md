# 🏥 Hospital Management Dashboard | Power BI Project

## 📌 Project Overview
This project is an end-to-end **Hospital Management Analytics Dashboard** built using **Power BI**.  
It provides insights into hospital operations, doctor performance, appointment trends, and financial billing analysis.

The dashboard is designed to help hospital management make data-driven decisions by tracking key operational and financial KPIs such as appointment status, cancellation rates, revenue trends, and doctor specialization performance.

---

## 🎯 Project Objectives
The main objectives of this project are:

- Monitor hospital appointment activity and trends over time  
- Analyze appointment statuses (Completed, Cancelled, Scheduled, No-show)  
- Evaluate doctor performance based on appointment volume and cancellation rate  
- Track total revenue and payment methods  
- Identify operational issues such as high no-show rates and appointment cancellations  
- Provide interactive reporting for decision-makers

---

## 📂 Dataset Information
The dataset was obtained from Kaggle:

**Hospital Management Dataset**  
Includes structured multi-table hospital records such as patients, doctors, appointments, treatments, and billing.

### Dataset Tables:
- **patients.csv** → Patient demographics and registration details  
- **doctors.csv** → Doctor profiles, specialization, and hospital branch  
- **appointments.csv** → Appointment details and status tracking  
- **treatments.csv** → Treatment types and associated costs  
- **billing.csv** → Billing amounts, payment methods, and payment status  

---

## 🏗️ Data Model (Schema Design)
The project uses a relational data model with the following relationships:

- `doctors (1) → appointments (*)`
- `patients (1) → appointments (*)`
- `appointments (1) → treatments (*)`
- `treatments (1) → billing (*)`
- `patients (1) → billing (*)`

This model supports efficient filtering and analysis across all hospital operations.

---

## 📊 Dashboard Pages & Key Insights

### 1️⃣ Hospital Insights (Executive Overview)
Provides a high-level overview of hospital performance.

#### KPIs Included:
- Total Doctors
- Total Patients
- Total Appointments
- Cancellation Rate %
- Total Revenue

#### Key Visuals:
- Total Appointments by Status
- Total Appointments by Day of Week
- Total Revenue Trend by Month
- Total Revenue by Payment Method

---

### 2️⃣ Appointment Operations Dashboard
Focused on appointment trends and operational performance.

#### Insights Covered:
- Monthly appointment activity
- Completed appointment trends
- Appointment distribution by status
- No-show analysis by specialization
- Appointment reasons analysis (Checkup, Consultation, Emergency, etc.)

#### Key Visuals:
- Appointments and Completed Rate per Month
- Appointment Status Distribution (Donut Chart)
- No-show per Specialization (Treemap)
- Appointments by Reason for Visit and Status (100% Stacked Bar)

---

### 3️⃣ Doctor Performance Dashboard
Analyzes doctors and specializations performance.

#### KPIs Included:
- Total Appointments per Doctor
- Total Appointments per Specialization
- Cancellation Rate per Doctor

#### Key Visuals:
- Total Appointments by Specialization
- Total Appointments per Doctor (Top Doctors)
- Doctor Performance Table (Completed vs Cancelled)

---

## 🧮 Key Measures (DAX)
The project includes multiple DAX measures such as:

- Total Patients  
- Total Doctors  
- Total Appointments  
- Completed Appointments  
- Cancelled Appointments  
- Cancellation Rate %  
- Total Revenue  
- Revenue by Payment Method  

---

## 🛠 Tools & Technologies Used
- **Power BI Desktop**
- **Power Query** (Data Cleaning & Transformation)
- **DAX** (Measures & KPIs)
- **Data Modeling** (Relationships between tables)
- **Interactive Dashboard Design** (Slicers, Filters, Navigation Buttons)

---

## 📌 Key Business Questions Answered
- What is the overall cancellation rate and how does it vary by month?
- Which specializations have the highest number of no-show appointments?
- Which doctors have the highest appointment volume?
- What is the revenue trend over the year?
- Which payment method generates the highest revenue?

---

## 📷 Dashboard Preview
📌 Screenshots of the dashboard are included in the repository.

---

## 🚀 How to Use the Project
1. Download the `.pbix` file from this repository  
2. Open it using **Power BI Desktop**  
3. Refresh the data if needed  
4. Explore the dashboard using slicers and navigation buttons  

---

## 📌 Future Improvements
- Add a dedicated Date Table for advanced time intelligence
- Add drill-through pages (Doctor Profile / Patient Profile)
- Add tooltip pages for deeper insights
- Enhance financial analysis (Paid vs Unpaid, Outstanding amounts)

---



---

## ⭐ If you like this project, consider giving it a star!
