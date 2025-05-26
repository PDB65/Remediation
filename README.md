## DISA STIG Remediations - (Windows 10)

![image](https://github.com/user-attachments/assets/d4e86ff9-9b40-4362-8f23-8055f39edc7f)


- Defense Information Systems Agency Security Technical Implementation Guide. 
- A set of cybersecurity configuration standards to secure IT systems and software.

---
## Attackers are constantly looking for vulnerabilities in systems and applications. 
- Reduce Vulnerabilities:  Scan the system, locate the vulnerability, and remediate.
  
 ![image](https://github.com/user-attachments/assets/c6ec3501-0a11-45e1-87e6-e9605e826bc0)

**Vulnerability:**
STIG ID: **WN10-CC-000145** - Users must be prompted for a password on resume from sleep (on battery).


**Purpose:** Data Execution Prevention (DEP) prevents harmful code from running in protected memory locations reserved for Windows and other programs.

![image](https://github.com/user-attachments/assets/22788419-18e3-436a-ade1-cded3f3f0be1)

- Configure the policy value for Computer Configuration >> Administrative Templates >> System >> Power Management >> Sleep Settings >> 'Require a password when a computer wakes (on battery)' to 'Enabled'.
  

- Click the link [STIGS](https://github.com/PDB65/Burwell_P/tree/main/STIGS) to view PowerShell Scripts to remediate Windows 10 DISA STIGs.
  
![image](https://github.com/user-attachments/assets/b16a3781-a405-4ee9-9814-51ea337b6443)

- Scan the system again to confirm the STIG was remediated.

  ![image](https://github.com/user-attachments/assets/03975558-21d6-48ee-b794-6a000116167a)
