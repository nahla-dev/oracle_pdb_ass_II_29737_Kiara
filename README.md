# oracle_pdb_ass_II_29737_Kiara
Practical assignment for Oracle Database 21c XE: creating and managing Pluggable Databases (PDBs), user accounts, and using Oracle Enterprise Manager (OEM).

# Oracle Pluggable Database Assignment II

Student Name: Kiara Nahla Tuyikunde  
Student ID: 29737  
Course: Oracle Database 21c XE – Practical Assessment  
Date: 15-Feb-2026  

 Overview

This assignment demonstrates the practical use of Oracle Multitenant Architecture, including:

- Creating and managing **Pluggable Databases (PDBs) 
- Creating and managing **users** inside a PDB  
- Using Oracle Enterprise Manager (OEM) to monitor the database  

All tasks were completed using **Oracle Database 21c Express Edition (XE).

## Oracle Environment

- Database Version: Oracle 21c XE  
- Tools Used: SQL*Plus, PowerShell, Oracle Enterprise Manager  
- Operating System: Windows 10/11  

## Tasks Completed

 1. Create a Pluggable Database

- PDB Name: `KI_PDB_29737`  
- Admin User: `Kiara_plsqlauca_29737`  
- Password: `Kiara123`  

Steps:

1. Connected as `SYS AS SYSDBA`.  
2. Verified existing PDBs.  
3. Opened the new PDB.  
4. Switched session to the new PDB.  
5. Created and unlocked the user with proper privileges.

### 2. Create and Delete a Temporary PDB

Temporary PDB Name: `KI_TO_DELETE_PDB_29737`

Steps:

1. Created the temporary PDB.  
2. Verified it exists.  
3. Deleted it completely.

---

### 3. Oracle Enterprise Manager (OEM)

- Logged in to OEM.  
- Verified the PDBs and user account are visible and active.  

## Challenges and Solutions

- **Login errors:** Solved by unlocking the user and using the correct password case.  
- **“Not connected” errors:** Solved by connecting first as SYS and then switching to the PDB.  
- **Shell confusion:** Learned that the `SQL>` prompt is where all commands are run.  

## Integrity Statement

I confirm that all work in this assignment is my own and completed honestly.

**Repository Name:** `oracle_pdb_ass_II_29737_Kiara`  
**Visibility:** PUBLIC
