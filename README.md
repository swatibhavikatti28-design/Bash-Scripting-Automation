# Bash-Scripting-Automation# Bash Scripting Automation Assignment
CampusPe - Cybersecurity Track

Name: Swati Bhavikatti  
Course: Cybersecurity  
Assignment: Bash Scripting Automation  
Total Questions Attempted: 5/5  

------------------------------------------------------------
PROJECT OVERVIEW
------------------------------------------------------------

This assignment demonstrates practical implementation of
Linux automation using Bash scripting. The project includes
system information display, file management, log analysis,
backup automation, and user account reporting.

All scripts were tested on Ubuntu/Linux environment.

------------------------------------------------------------
FILES INCLUDED
------------------------------------------------------------

q1_system_info.sh      - Displays formatted system information
q2_file_manager.sh     - Menu-driven file & directory manager
q3_log_analyzer.sh     - Log file statistics analyzer
q4_backup.sh           - Automated backup script
q5_user_report.sh      - System user account reporting tool
README.txt             - Project documentation
Sample Outputs         - Screenshots / text output files

------------------------------------------------------------
HOW TO RUN THE SCRIPTS
------------------------------------------------------------

Make scripts executable:

chmod +x *.sh

------------------------------------------------------------
Q1: System Information
------------------------------------------------------------

Run:
./q1_system_info.sh

Displays:
- Username
- Hostname
- Date & Time
- OS Name
- Current Directory
- Home Directory
- Logged-in Users
- System Uptime

------------------------------------------------------------
Q2: File & Directory Manager
------------------------------------------------------------

Run:
./q2_file_manager.sh

Features:
- List files
- Create directory
- Create file
- Delete file (with validation)
- Rename file
- Search file
- Count files and directories

------------------------------------------------------------
Q3: Log Analyzer
------------------------------------------------------------

Run:
./q3_log_analyzer.sh access.log

Features:
- Total entries count
- Unique IP addresses
- Status code summary
- Top 3 IP addresses
- Most accessed page

------------------------------------------------------------
Q4: Backup Script
------------------------------------------------------------

Run:
./q4_backup.sh

Features:
- Source directory selection
- Backup destination
- Copy or tar.gz archive
- Timestamped backup file
- Size & duration calculation

------------------------------------------------------------
Q5: User Report
------------------------------------------------------------

Run:
sudo ./q5_user_report.sh

Features:
- User statistics
- Regular user table
- Group information
- Security checks
- Root privilege detection
- Inactive users

------------------------------------------------------------
TESTING ENVIRONMENT
------------------------------------------------------------

Operating System: Ubuntu Linux
Shell: Bash
Tested using:
- bash -n script.sh (syntax check)
- bash -x script.sh (debugging)
- shellcheck (linting)

------------------------------------------------------------
CHALLENGES FACED
------------------------------------------------------------

- Formatting output tables using awk
- Handling file validation and error messages
- Parsing /etc/passwd and /etc/group correctly
- Managing user input safely
- Implementing timestamped backup naming

------------------------------------------------------------
LEARNING OUTCOMES
------------------------------------------------------------

- Bash scripting fundamentals
- File and directory operations
- Text processing using awk, grep, sort, uniq
- System automation techniques
- Linux user and permission management

------------------------------------------------------------
END OF DOCUMENT
------------------------------------------------------------
