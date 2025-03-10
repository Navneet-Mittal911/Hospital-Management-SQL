#  Hospital Management System Database

## About This Project
Managing hospital data efficiently can be a challenge. This project aims to simplify things with a **Hospital Management System Database**, built using **SQL**. It includes well-structured tables for handling patients, doctors, appointments, medical records, billing, staff, inventory, and pharmacy stock, making hospital operations smoother.

##  Database Structure
### **Database Name**: `hospital_management`

### **Tables & What They Do**

#### 1. Patients
Stores basic details about patients, including their contact information, blood type, and insurance details.

#### 2. Patient_Addresses
Keeps track of patients' addresses separately for better organization.

#### 3. Doctors
Contains information about doctors, including their specialization, experience, and contact details.

#### 4. Appointments
Manages patient appointments with doctors, tracking date, time, reason, and status.

#### 5. Medical Records
Stores records of patient visits, tracking which doctor attended them and when.

#### 6. Diagnosis
Links medical records to diagnoses and prescriptions.

#### 7. Billing
Handles patient billing, storing details about charges and payment status.

#### 8. Payment Details
Keeps records of payments made against hospital bills, including payment method and amount.

#### 9. Staff
Stores details of hospital staff, including roles, salaries, and shift timings.

#### 10. Rooms
Manages hospital rooms, tracking their availability and occupancy status.

#### 11. Admissions
Tracks patient admissions, linking them to rooms and recording discharge details.

#### 12. Inventory
Maintains stock records of hospital equipment and medical supplies.

#### 13. Suppliers
Keeps information about suppliers providing medical and pharmaceutical products.

#### 14. Tests
Stores available lab tests and their pricing details.

#### 15. Lab Reports
Tracks lab test reports, linking them to patients and doctors.

#### 16. Test Results
Stores results of various medical tests conducted on patients.

#### 17. Pharmacy
Manages medicine details, including categories and pricing.

#### 18. Stock
Tracks medicine availability, stock levels, and expiry dates.

## How to Use
1. **Set up the database**:
   ```sql
   CREATE DATABASE hospital_management;
   USE hospital_management;
   ```
2. **Create the tables** by running the SQL script.
3. **Insert some sample data** to start testing.
4. **Run queries** to fetch and manipulate hospital data.

##  Installation Requirements
- Install **MySQL Server** (or a compatible database system).
- Use a SQL client like **MySQL Workbench, DBeaver, or phpMyAdmin**.
- Load the provided SQL schema to set up the database.
