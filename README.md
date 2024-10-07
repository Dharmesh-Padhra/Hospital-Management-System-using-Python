# Hospital Management System

A CLI-based Hospital Management System built using Python in Jupyter Notebook. The system allows patients to create accounts, log in, and retrieve their latest prescriptions. Admins can add doctor accounts, and doctors can create prescriptions for patients. All data, including account credentials and medicine details, is stored in text files.

## Features

- **Patient Account Management**: Patients can create accounts, log in, and view their latest prescription.
- **Admin Management**: Admins have the ability to add new doctor accounts to the system.
- **Doctor Features**: Doctors can create prescriptions for patients, which include:
  - Patient and doctor details
  - Remarks about the patient's health condition
  - A list of prescribed medicines
  - Total cost of the medicines
- **Prescription Storage**: Prescriptions are stored as text files and contain detailed information about the consultation.
- **Search Functionality**:
  - **Patients** can search for doctors based on the name, email, phone number, or bio.
  - **Doctors** can search for medicines available in the hospital while adding them to prescriptions. If a search keyword matches a unique medicine, the system automatically asks for the quantity. If multiple results are found, it displays a list to choose from.

## System Overview

- **Patients**: Can create an account, log in, search for doctors, and retrieve their latest prescription.
- **Admins**: Can add new doctor accounts to the system.
- **Doctors**: Can create and manage prescriptions for patients, and search for medicines in the hospital.

## Data Storage

All data is stored in text files:
- Account credentials (username and password)
- Medicine details (name, quantity, price)
- Doctor details (name, email, phone, bio)
- Prescription files with doctor and patient details

## Prescription Format

The prescription is saved as a text file, containing:
- Doctor's name
- Patient's name
- Remarks
- List of medicines with their prices
- Total cost of medicines

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/hospital-management-system.git
