# -Cybersecurity-Lab-Environment-W1-Extar-Project
Week 1 Extra Project: Setting Up Windows 10 and Android 9 Virtual Machines Using VMware
Project Overview
This project was completed as part of the Cybersecurity Internship Program at Networkwalks (Batch B084).
The purpose of this lab was to install and configure Windows 10 and Android 9 virtual machines using VMware and test network connectivity between Kali Linux and Windows 10.
Objectives
•	Install and configure Windows 10 and Android 9 virtual machines in VMware.
•	Set up the virtual machines successfully.
•	Identify the IP addresses of Kali Linux and Windows 10.
•	Test network connectivity using the ping command.
•	Troubleshoot network connectivity issues.
Tools and Technologies Used
•	VMware Workstation
•	Kali Linux
•	Windows 10
•	Android 9
•	Networking commands: ifconfig, ipconfig, and ping
Project Implementation
1. Virtual Machine Setup
Installed and configured Windows 10 and Android 9 virtual machines using VMware.
2. IP Address Identification
Identified the IP addresses of the machines using the following commands:
Kali Linux:
bash
ifconfig
Windows 10:
cmd
ipconfig
3. Network Connectivity Testing
Used the ping command to test communication between Kali Linux and Windows 10.
The test was successful, confirming that both machines could communicate over the network.
Challenges Faced
One of the main challenges encountered during this lab was that Windows 10 was not responding to ping requests from Kali Linux.
Solution
After troubleshooting, I discovered that Windows Defender Firewall was blocking incoming ICMP echo requests.
I adjusted the Windows Firewall settings to allow the necessary ICMP traffic.
After making the changes, I repeated the ping test and successfully received replies from the Windows machine.
Key Learnings
Through this project, I gained practical knowledge and experience in:
•	Installing and configuring virtual machines.
•	Understanding basic networking concepts.
•	Identifying IP addresses.
•	Testing connectivity between virtual machines.
•	Troubleshooting network communication issues.
•	Understanding the role of firewalls in network security.
Conclusion
This project provided valuable hands-on experience in virtual machine configuration and basic network troubleshooting.
It also helped me understand how firewall configurations can affect communication between devices on a network.
I look forward to applying these skills in future cybersecurity projects.
