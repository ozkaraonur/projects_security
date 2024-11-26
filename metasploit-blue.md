# Blue

## Objective

The Blue lab focuses on exploiting the EternalBlue vulnerability (MS17-010) on Windows machines. It emphasizes understanding SMBv1 vulnerabilities and securing systems against them.

### Skills Learned

  - SMB protocol analysis and exploitation.
  - Understanding EternalBlue vulnerability (MS17-010).
  - Methods for securing Windows systems.

### Tools Used

  - Metasploit Framework: For EternalBlue exploitation.
  - Nmap: For SMB service detection and scanning.
  - John: For cracking user password's hash..

## Steps

1. Detect SMBv1 Services

   - Scan the target machine for SMB services:
![Screenshot_2024-11-26_20_56_32(1)](https://github.com/user-attachments/assets/8e6b9b92-4521-4a52-ac9c-80bde9e85d4c)

2. Exploit Execution

   - Execute the EternalBlue exploit:
   ![yyyy(1)](https://github.com/user-attachments/assets/b4b3488c-83ac-4cb1-89d3-1366508ae7f0)



3. Post-Exploitation

   - Extract system details and escalate privileges:
    ![hAHSUYMNP](https://github.com/user-attachments/assets/174d446f-1f96-413f-b743-58082f8b749b)
    ![JOHN](https://github.com/user-attachments/assets/cdaf96b9-dfa9-4296-aead-09f785a8dd44)
    ![flag](https://github.com/user-attachments/assets/b3b24c8e-9f00-469d-a1c5-608e2fe0c5bc)
