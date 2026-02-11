Oracle Pluggable Database Assignment II

Overview of Tasks
- Task 1: PDB creation  
- Task 2: Temporary PDB creation and deletion  
- Task 3: OEM dashboard access  
- Task 4: Documentation & Reporting  

Oracle Environment Used
- Oracle Database version: 21.3.0.0.0  
- Tools: SQL*Plus, Oracle Enterprise Manager Express (OEM Express)  
- Host environment: Windows 10  

Explanation of Each Task

Task 1: PDB Creation
- Created pluggable database.  
- Verified using SHOW PDBS;  

Task 2: Temporary PDB Creation and Deletion
For this task, I created a temporary pluggable database to demonstrate the process of provisioning and removal.  
- Creation: A temporary PDB was created using SQL commands.  
- Deletion: The temporary PDB was then dropped using the DROP PLUGGABLE DATABASE command.  
- Verification: After deletion, SHOW PDBS; confirmed that the temporary PDB was removed successfully.  

Task 3: OEM Dashboard
- Accessed OEM Express at https://localhost:5500/em.  

Task 4: Documentation & Reporting
- Prepared this README.md.  
- Published screenshots in the screenshots/ folder.  

Challenges Faced
During the assignment, I encountered difficulties accessing Oracle Enterprise Manager Express (OEM Express). Specifically:  
- Login attempts returned the error “Invalid Container Name”, even when using the correct SYS credentials.  
- A secondary browser authentication popup appeared, requiring login again, but this did not resolve the issue.  

These challenges were addressed by verifying container names in SQL*Plus, confirming listener status, and testing with the SYSTEM account instead of SYS.  

Integrity Statement
I confirm that all work in this repository is my own, completed honestly and without unauthorized assistance.
