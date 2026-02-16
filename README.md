Oracle Pluggable Database Assignment

Overview
This assignment demonstrates creating and managing Oracle Pluggable Databases (PDBs) in a multitenant environment using Oracle Database 21c on Windows 10.
Task 1: Creating My PDB
I created a permanent PDB named Em_pdb_27617 for classwork. After connecting as SYSDBA, I created the PDB, opened it, and set up my user account Emmelance_plsqlauca_27617 with full privileges. The PDB is working perfectly and ready for future assignments.
Task 2: Temporary PDB Lifecycle
I created a temporary PDB called Em_to_delete_pdb_27617, verified it existed, then deleted it completely including all datafiles. This showed me the full lifecycle management of PDBs - an important skill for database administration.
Task 3: Oracle Enterprise Manager
I accessed OEM at https://localhost:5501/em and logged in as SYS with SYSDBA role. The dashboard clearly shows all my PDBs and provides a good overview of database status and performance.
Challenges
The biggest challenge was dealing with special characters in my password. The @ symbol caused connection errors, so I switched to a simpler password. I also had to bypass the SSL warning in my browser when accessing OEM, which is normal for self-signed certificates.
What I Learned
This assignment taught me hands-on PDB management - creating, monitoring, and deleting them. I now understand how Oracle's multitenant architecture works and how to use both command-line tools and graphical interfaces for database administration.
Screenshots
All evidence is in the screenshots/ folder showing PDB creation, deletion, and OEM dashboard access.
Integrity Statement
I completed this assignment independently. All commands were executed in my Oracle environment and screenshots are authentic.
Emmelance - Student ID: 27617
