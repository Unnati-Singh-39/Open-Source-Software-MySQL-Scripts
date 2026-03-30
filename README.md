## Open Source Software Audit - MySQL

## Name: [Unnati Singh]
## Registration Number: [24BAI10625]
## Chosen Software: MySQL

This repository contains Bash shell scripts created as part of my Open Source Software (OSS) course project.

The goal of this project was to understand how MySQL, an open-source database, works in a Linux environment and to practice basic shell scripting, system auditing, and database management concepts.

_______________

## What I Learned
	•	Installing and verifying open-source software on Linux (Ubuntu)
	•	Working with directories, permissions, and system logs
	•	Shell scripting fundamentals: variables, loops, conditions, and functions
	•	Monitoring and analyzing system logs for errors and warnings
	•	Creating automated MySQL backups and checking service status
	•	Integrating practical auditing techniques for open-source software

________________

## Scripts Included

Script	Purpose
| Script     | Purpose                                                                                      |
| ---------- | -------------------------------------------------------------------------------------------- |
| script1.sh | Displays system information (user, home directory, kernel version, uptime, date/time)        |
| script2.sh | Checks if MySQL is installed and shows its description                                       |
| script3.sh | Audits critical directories and MySQL configuration directory; displays permissions and size |
| script4.sh | Reads a log file and counts occurrences of a keyword (default: “error”)                      |
| script5.sh | Creates a timestamped backup of all MySQL databases and shows MySQL service status           |

________________

## How to Run
Open your terminal (Ubuntu / Linux VM) and navigate to the folder containing the scripts.

## Run the scripts using:
  bash script1.sh
  bash script2.sh
  bash script3.sh
  sudo bash script4.sh /var/log/syslog error
  sudo bash script5.sh

Note: Some scripts, especially script4.sh and script5.sh, require sudo permissions to access system logs or perform MySQL backups.
_________________

## Project Structure
OpenSource-MySQL-Audit
│
├── script1.sh
├── script2.sh
├── script3.sh
├── script4.sh
├── script5.sh
└── README.md
_________________

## Requirements
	•	Linux environment (Ubuntu recommended; can run in a VM like UTM)
	•	MySQL installed and configured
	•	Basic terminal knowledge
	•	Sudo privileges for some scripts

_________________

## Notes
	•	script4.sh requires a log file (like /var/log/syslog) and optionally a keyword.
	•	script5.sh automatically creates a backup directory (~/mysql_backups) and logs the backup process.
	•	All scripts were executed and tested on Linux (Ubuntu VM) and are compatible with standard Bash shells.
	•	Each script demonstrates practical open-source auditing and scripting concepts, useful for system administration and database management.

_________________

## Conclusion
   This project improved my understanding of MySQL on Linux and strengthened my practical skills in shell scripting and system auditing.
