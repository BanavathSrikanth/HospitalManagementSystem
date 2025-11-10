# Hospital Management System (Java + JDBC)

A simple console app to manage patients, doctors, and appointments.

## Tech Stack
- Java 17 (or 11+), JDBC
- MySQL 8.x

## Features
- Add & view patients
- View doctors
- Book appointments (prevents double-booking for the same doctor and date)

## Setup
1. Create DB and tables:
   - Run `schema.sql` to create `hospital`, `patients`, `doctors`, `appointments`.
2. Configure DB credentials:
   - Set environment variables:
     - `DB_URL=jdbc:mysql://localhost:3306/hospital`
     - `DB_USER=your_user`
     - `DB_PASS=your_pass`
3. Build & run:
   - `javac -cp .:mysql-connector-j.jar src/HospitalManagementSystem/*.java`
   - `java  -cp .:mysql-connector-j.jar HospitalManagementSystem.HospitalManagementSystem`

## Sample Credentials
- None required; app is CLI based.

## Screenshots
_Add 1–2 console screenshots here._
