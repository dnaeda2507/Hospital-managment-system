Hospital Management System Database Design
This project involves the creation of a normalized database to manage hospital operations, including appointments, patient treatment, and staff management. The system aims to track various hospital activities and provide insights into patient treatments, appointments, and interactions with hospital staff.

Features
List of all doctors that have seen a certain patient
A query feature to fetch all doctors who have interacted with a particular patient.

List of all patients and the number of appointments they have had in the past year
A query to retrieve a list of patients and their appointment counts over the past year.

Changing the date of an appointment
Allows the modification of appointment dates for patients.

Adding a test for a patient
Provides a way to add new medical tests for a patient to the system.

Removing an appointment from the system
Allows the deletion of appointments from the system.

Database Design
The database has been normalized to 3NF (Third Normal Form) for efficient storage and retrieval of hospital data. 
The system tracks:
Patients
Doctors
Appointments (including follow-ups)
Tests
Hospital Staff (including nurses )

ER Diagram
An Entity-Relationship Diagram (ERD) has been created to represent the relationships between the entities. It includes cardinality and participation information (e.g., 1..1, 0..*, etc.) for accurate database modeling.

SQL Queries
The SQL queries to:

Create tables for storing data in the 3NF schema.
Insert data from the unnormalized dataset into the normalized tables.
Create views to recreate the original unnormalized dataset from the 3NF tables for comparison purposes.
are available in the sql.docx/ folder.

Unnormalized Dataset
The unnormalized dataset has been prepared and is available in the NFTtable.xlsx/ folder as a spreadsheet. This data serves as the starting point for the normalization process.
