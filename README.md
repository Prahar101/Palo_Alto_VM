Security using Palo Alto Next-Generation Firewall (NGFW)
Project Overview:
This project demonstrates the configuration, security policies, and attack prevention techniques using Palo Alto NGFW in a simulated environment. The implementation focuses on Zero Trust Architecture, intrusion prevention, URL filtering, antivirus inspection, and SIEM-based monitoring to enhance cybersecurity.

Key Features & Configurations
1. Network Setup & Segmentation
-Configured Inside-Host, DMZ-Host, and Kali Linux with unique subnets to establish controlled traffic flow.
-Verified network isolation and implemented Zero-Trust Security to restrict unauthorized communication.
2. Firewall Rules & Access Control
-Configured firewall policies to allow/deny traffic based on security best practices.
-Implemented application-aware policies instead of traditional port-based filtering.
3. Web Filtering & URL Access Control
-Applied URL filtering rules to block Facebook Messenger and testfire.net while allowing general web access.
-Enforced HTTPS Inspection for enhanced visibility into encrypted traffic.
4. Intrusion Detection & Threat Prevention
-Integrated Intrusion Prevention System (IPS) with custom rules to detect and block MS17-010 EternalBlue exploit.
-Configured SIEM logging and firewall monitoring for real-time threat visibility.
5. Secure Remote Access & Authentication
Deployed Telnet & SMB access controls in a segmented network.
-Verified security through penetration testing using Metasploit and adjusted firewall rules accordingly.
6. Advanced Threat Protection
-Configured Antivirus inspection to block malware downloads using EICAR test files.
-Created custom IPS rules with CVE-based signatures to mitigate critical vulnerabilities.

--> Exploitation & Attack Simulations
-Used Metasploit to execute the MS17-010 EternalBlue exploit on the DMZ-Host.
-Implemented reverse shell protection using firewall policies to prevent unauthorized access.
-Applied IPS vulnerability signatures to detect and log attack attempts.

--. Results & Security Enhancements
-Successfully blocked unauthorized traffic while maintaining legitimate network functions.
-Implemented Palo Alto logging & SIEM integration for monitoring and forensic analysis.
-Hardened the network against real-world exploits and unauthorized lateral movement.

-->Repository Content:
Project Report detailing configurations, firewall rules, security policies, and testing results.
Screenshots showcasing firewall policies, attack attempts, and security measures in action.

Contact:
If you're interested in discussing this project further or have any queries, feel free to reach out:

📧 Email: prahars25@gmail.com
🔗 LinkedIn: https://www.linkedin.com/in/prahar-shah-238741207
