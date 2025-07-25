Localhost Port Scan Using Nmap

Project Overview

This project demonstrates the **reconnaissance phase of ethical hacking** by scanning the localhost (`127.0.0.1`) using **Nmap**, a powerful network exploration and security auditing tool. It helped me understand how open ports and services can reveal system vulnerabilities and how attackers gather this data.

Objectives

- Learn and perform **active reconnaissance**
- Identify **open ports and running services**
- Understand the role of **Nmap in penetration testing**
- Gain hands-on experience using **Command Line Tools**

Tools & Technologies Used                                                           

1.Nmap             
Purpose: Network scanning, service version detection            
2.Command Prompt  
Purpose: Run scans and interact with system from CLI     
3.Windows 10       
Purpose: Operating system used for testing and analysis         
4. 127.0.0.1        
Purpose: Loopback address for safe, offline practice            


Commands Used

bash
nmap 127.0.0.1             # Basic localhost scan  
nmap -sV 127.0.0.1         # Detect service versions  
nmap -A 192.168.1.1        # Aggressive scan (OS + scripts)  
