# Oracle Pluggable Database Administration Assignment 2

## Student Information
- Name: Joseph
- Student ID: 19939/2022
- Course: Database Programming (C11665)

---

## 1. Assignment Overview
This assignment demonstrates Oracle Multitenant architecture by creating, managing, and deleting Pluggable Databases (PDBs). It also includes user creation, privilege assignment, Oracle Enterprise Manager usage, and GitHub documentation.

---

## 2. Oracle Environment
- Oracle Database: XE 21c (21.3.0.0.0)
- OS: Windows 64-bit
- SQL Developer: 23.1.1
- Tool: Oracle Enterprise Manager Database Express

---

## 3. Task 1: PDB Creation and User Configuration
A Pluggable Database named:

- jo_pdb_19939_2022

was successfully created and opened.

Inside the PDB, a user was created:

- joseph_plsqlauca_19939_2022

Privileges were granted including:
CREATE SESSION, CREATE TABLE, CREATE VIEW, CREATE SEQUENCE, CREATE PROCEDURE, and UNLIMITED TABLESPACE.

Successful login was verified.

---

## 4. Task 2: Temporary PDB Creation and Deletion
A temporary PDB named:

- jo_to_delete_pdb_19939_2022

was created, verified, opened, and then deleted successfully using INCLUDING DATAFILES.

---

## 5. Task 3: Oracle Enterprise Manager (OEM)
Oracle Enterprise Manager Database Express was accessed successfully, showing:
- CDB environment
- Database status
- PDB information

---

## 6. Challenges and Solutions
The main challenge was insufficient privileges when attempting PDB operations using SYSTEM. This was solved by using SYSDBA privileges.

---

## 7. Lessons Learned
- Oracle Multitenant Architecture
- Creating and managing PDBs
- User creation and privilege management
- OEM navigation
- GitHub documentation

---

## 8. Integrity Statement
I confirm that this work is my own and all screenshots and documentation are original.
