# Ethical Hacking Task 02
## Network Scanning & Service Enumeration

=========================================================
Student Information
=========================================================

Name        : Stephen J
Internship  : White Band Associates
Task        : Ethical Hacking Task 02
Topic       : Network Scanning & Service Enumeration
Tool Used   : Nmap
Operating System : Ubuntu Linux

=========================================================
Objective
=========================================================

The objective of this task is to learn the fundamentals
of network scanning and service enumeration using Nmap.
The task demonstrates how to identify open ports,
running services, service versions, and operating system
information in a safe and authorized environment.

=========================================================
Software & Tools Used
=========================================================

• Ubuntu Linux
• Nmap
• Terminal
• GitHub

=========================================================
Commands Executed
=========================================================

1. Verify Nmap Installation

Command:
nmap --version

Purpose:
Checks whether Nmap is installed successfully.

---------------------------------------------------------

2. Localhost Scan

Command:
nmap localhost

Purpose:
Scans the local machine to identify open ports and
running services.

---------------------------------------------------------

3. Service Version Detection

Command:
nmap -sV localhost

Purpose:
Displays the version of services running on open ports.

---------------------------------------------------------

4. Operating System Detection

Command:
sudo nmap -O localhost

Purpose:
Attempts to identify the operating system of the target.

=========================================================
Screenshots
=========================================================

Screenshot 1
Title : Nmap Installation

Description:
Shows that Nmap has been successfully installed.

Image:
Screenshots/01_Nmap_Installation.png

---------------------------------------------------------

Screenshot 2
Title : Nmap Version

Description:
Displays the installed version of Nmap.

Image:
Screenshots/02_Nmap_Version.png

---------------------------------------------------------

Screenshot 3
Title : Localhost Scan

Description:
Shows the list of open ports and running services
detected on localhost.

Image:
Screenshots/03_Localhost_Scan.png

---------------------------------------------------------

Screenshot 4
Title : Service Version Detection

Description:
Shows the detected versions of running services.

Image:
Screenshots/04_Service_Version.png

---------------------------------------------------------

Screenshot 5
Title : Operating System Detection

Description:
Shows the operating system detected using Nmap.

Image:
Screenshots/05_OS_Detection.png

=========================================================
Project Folder Structure
=========================================================

Ethical_Hacking_Task_02_Stephen_J/

│── README.md
│── Scan_Report.pdf
│── Research_Notes.txt
│── Screenshots/
│   ├── 01_Nmap_Installation.png
│   ├── 02_Nmap_Version.png
│   ├── 03_Localhost_Scan.png
│   ├── 04_Service_Version.png
│   └── 05_OS_Detection.png

=========================================================
Learning Outcomes
=========================================================

• Learned how to install and verify Nmap.
• Understood how to perform a localhost scan.
• Identified open ports and running services.
• Learned service version detection.
• Understood operating system fingerprinting.
• Improved knowledge of safe and ethical network scanning.

=========================================================
Conclusion
=========================================================

This task provided practical experience with Nmap and
its scanning capabilities. I learned how to identify
open ports, detect running services, perform service
version detection, and identify the operating system.
The task also highlighted the importance of securing
unnecessary open ports and regularly monitoring systems
for potential vulnerabilities. Most importantly, I
understood that network scanning should always be
performed responsibly and only on systems for which
proper authorization has been obtained.

=========================================================
GitHub Repository
=========================================================

Upload the following files to your GitHub repository:

✔ README.md
✔ Scan_Report.pdf
✔ Research_Notes.txt
✔ Screenshots Folder

=========================================================
End of README
=========================================================
