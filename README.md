## [ Medical Management System- ]

## Author
      **Akshay Sharma**

# Overview:-
The Medical Management System is a desktop application designed to manage patient prescriptions and medical records. Built using Python's Tkinter for the graphical user interface and MySQL for database management, this system provides a user-friendly interface to add, view, and manage medical records effectively.

## Features:-
# Add Patient Records:
Allows users to input and store patient details, including medication information, prescription details, and personal data.

# View Records: 
Provides a function to display all stored patient records in a scrollable window.

# Generate Prescriptions: 
Automatically formats and displays prescription details based on the entered data.

# Clear Entries: 
Option to clear all input fields to enter new data.

# Database Management: Uses MySQL to handle data storage and retrieval, ensuring data persistence and integrity.

## Installation

# Install Dependencies: Ensure you have Python installed, then install the required packages using pip:
              **pip install mysql-connector-python**
              
# Set Up MySQL:
Ensure MySQL is installed and running.
Create a database named medical_system and run the provided SQL commands to create the necessary table.

# Run the Application:
Navigate to the directory where the script is located.

# Execute the Python script:
              **python medical_management_system.py**

## Usage

# Submit Data: 
Fill in all required fields and click "SUBMIT - DATA" to save the information to the database.

# Clear Entries: 
Click "CLEAR - ENTRY" to reset all fields.Show Data: Click "SHOW - DATA" to view all stored records.

# Prescription: Click "PRESCRIPTION" to generate a formatted prescription based on the entered details.

## Requirements
//Python 3.x
//Tkinter
//MySQL Server

## Database Schema

CREATE TABLE IF NOT EXISTS Medical (
    patient VARCHAR(225),
    nameoftablet VARCHAR(225),
    ref VARCHAR(225),
    dose VARCHAR(225),
    nooftablets VARCHAR(225),
    lot VARCHAR(225),
    issuedate VARCHAR(225),
    Expdate VARCHAR(225),
    dailydose VARCHAR(225),
    sideEffect VARCHAR(225),
    DOB VARCHAR(225),
    Furtherinfo VARCHAR(225),
    BloodPressure VARCHAR(225),
    storage VARCHAR(225),
    Medication VARCHAR(225),
    PatientID VARCHAR(225),
    contact VARCHAR(225),
    Address VARCHAR(225),
    fathername VARCHAR(225),
    dr VARCHAR(225)
);

LicenseThis project is licensed under the Akshay License. 
