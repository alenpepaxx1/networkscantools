# networkscantools

"""
=====================================================================================
 Advanced Network Scanner Tool
 Author: Alen Pepa
 License: For educational and ethical use only.
=====================================================================================

DISCLAIMER:
-----------
This software is developed strictly for educational and research purposes only.

By using this tool, you agree to the following:
 - You will only use this tool on networks and systems you own or have explicit permission to test.
 - Unauthorized scanning of networks or devices is illegal and punishable by law in many countries.
 - The author (Alen Pepa) and contributors take no responsibility for any misuse or damages caused.

Relevant Laws:
--------------
⚖️ USA: Computer Fraud and Abuse Act (CFAA)
⚖️ EU: General Data Protection Regulation (GDPR), Network and Information Systems Directive (NIS)
⚖️ UK: Computer Misuse Act 1990
⚖️ Albania: Law No. 9918 on Electronic Communications (Articles 30–35)
⚖️ International: Budapest Convention on Cybercrime

 How to use:

1. Make sure you have nmap installed and nmap.exe is in your system PATH (or adjust the NMAP_PATH variable).

2. Install required Python packages:

bash
Copy
Edit
pip install python-nmap scapy PySide6 requests
Run the script.

3. Enter the IP range to scan (default is 192.168.1.0/24).

4. Optionally enter ports to scan (like 22,80,443 or 1-1000).

5. Click Scan Network.

6. Click on any found device to scan its ports, services, OS, and get vendor/geolocation info.

7. Full Changelog: https://github.com/alenpepaxx1/networkscantools/commits/alenpepa
