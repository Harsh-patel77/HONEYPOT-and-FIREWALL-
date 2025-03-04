# HONEYPOT-and-FIREWALL-

# Project Summary: Implementing Honeypot and Firewall 

## Objective:
The goal of this project is to enhance the security of a Windows-based system by implementing a honeypot to detect and analyze potential cyber threats and configuring a firewall to prevent unauthorized access.

# Honeypot 
Honeypot Misleads attackers by creating decoy systems, reducing actual system exposure.
![Screenshot 2025-03-03 174310](https://github.com/user-attachments/assets/c340db9e-da51-4ef3-9a0c-42dbcc34b241)

Before deploying the attack, I performed a version scan, which took 61.37 seconds.
![Screenshot 2025-03-03 180804](https://github.com/user-attachments/assets/1b0e113d-4952-49ba-8fe5-0887155a55f0)

After deploying the honeypot, I performed a version scan again on the attacker's machine (as seen on the right side of the Windows screen). This time, the scan took 208.89 seconds. The scan interacted with the honeypot application, generating live log entries.

![Screenshot 2025-03-03 180713](https://github.com/user-attachments/assets/625ea80a-eb63-4fe5-bd95-0a71650023e0)
As observed on the attacker's side, the honeypot provides fake ports, misleading the attacker and concealing the actual running ports. This prevents the attacker from identifying the real services in operation. 
![Screenshot 2025-03-03 180828](https://github.com/user-attachments/assets/33f17c52-3c5b-408d-97db-1639f1108d79)


As observed in the honeypot logs, detailed information is recorded, including the date, time, remote IP, remote port, local IP, local port, protocol, and the number of bytes shared. These logs capture all essential details of the interaction, providing valuable insights into potential attacks

![Screenshot 2025-03-03 180930](https://github.com/user-attachments/assets/3cd03cb3-6aff-4263-9781-946391d0e2ad)







# FIREWALL 
Creating firewall rules helps regulate network traffic by allowing or blocking specific connections based on predefined security policies. This enhances system security by restricting unauthorized access and mitigating potential threats.

![Screenshot 2025-03-03 171439](https://github.com/user-attachments/assets/8b3da810-00c0-442e-a3fb-10200c0a1b09)


![Screenshot 2025-03-03 171721](https://github.com/user-attachments/assets/d0abc027-9c93-44a5-9033-3600e6b7f1bd)






