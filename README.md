# Ex-02 InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering

## Architecture Diagram
```
                      +-------------------------+
                      |     Attacker System     |
                      |     (Kali Linux)        |
                      +-----------+-------------+
                                  |
                                  | Terminal / Browser
                                  | Executes Recon Tools
                                  v
      +------------------- Passive Recon --------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   WHOIS Query  | --> |    Domain Registrars    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   DNS Enum     | --> |     Public DNS Servers  |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      +-----------------------------------------------------+

                                  |
                                  v

      +------------------ Active Recon ----------------------+
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  |   Nmap Scan    | --> |  Target Host/Network    |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | WhatWeb, Wapp | --> |   Target Web Application |  |
      |  +----------------+     +------------------------+  |
      |                                                     |
      |  +----------------+     +------------------------+  |
      |  | theHarvester   | --> |     Search Engines      |  |
      |  +----------------+     +------------------------+  |
      +-----------------------------------------------------+

                                  |
                                  v
                    +-----------------------------+
                    |     Collected Information   |
                    | - IPs, Subdomains           |
                    | - Open Ports & Services     |
                    | - Technology Stack          |
                    | - Emails, Metadata          |
                    +-----------------------------+
```

## OUTPUT:
### Whois
<img width="1638" height="912" alt="Screenshot 2025-09-08 092342" src="https://github.com/user-attachments/assets/24b9bc96-b225-4f06-a8c7-2fac6dd30b1d" />
<img width="1511" height="907" alt="Screenshot 2025-09-08 092432" src="https://github.com/user-attachments/assets/3909bfa3-4c9c-401d-bad9-6ec86a52ee52" />
<img width="1158" height="902" alt="Screenshot 2025-09-08 092448" src="https://github.com/user-attachments/assets/f08242f5-898d-4029-8349-8ffabeda988a" />

### Finding Hosting Company :
<img width="1716" height="909" alt="Screenshot 2025-09-08 092918" src="https://github.com/user-attachments/assets/288ff446-7909-490c-b72a-c82963292887" />

### History of the website :
<img width="1527" height="907" alt="Screenshot 2025-09-08 093802" src="https://github.com/user-attachments/assets/7d36ad69-9982-4f74-96db-1c65161f6638" />
<img width="1555" height="910" alt="Screenshot 2025-09-08 093953" src="https://github.com/user-attachments/assets/c609a1c9-bf52-47b3-a36d-54579bc15e81" />

### ping command :
<img width="1600" height="780" alt="image" src="https://github.com/user-attachments/assets/27f861a2-6d06-4d2c-b133-bd7dcb3e5e7d" />

### whois :
<img width="1600" height="780" alt="image" src="https://github.com/user-attachments/assets/c877bbb5-fad1-4af3-b33a-bebda65f6266" />

### netcat :
<img width="860" height="243" alt="image" src="https://github.com/user-attachments/assets/b0c14122-9bbd-4b2d-8154-1522f4386c4b" />

### nmap :
<img width="725" height="293" alt="image" src="https://github.com/user-attachments/assets/bccb9eff-5de5-4629-ba04-824f1efbf171" />

### whatweb :
<img width="1586" height="419" alt="image" src="https://github.com/user-attachments/assets/d70f0dd3-ff1f-47ea-96a5-87b410679eb1" />

### httprint :
<img width="571" height="310" alt="image" src="https://github.com/user-attachments/assets/306de0bb-efd9-4010-8cb4-6cdd27d66fb8" />

### TCP traceroute :
<img width="747" height="394" alt="image" src="https://github.com/user-attachments/assets/b94ac6c8-71b6-434b-821a-3841eb87ee7f" />

### UDP traceroute :
<img width="731" height="527" alt="image" src="https://github.com/user-attachments/assets/7151f23b-4cf4-4b10-82a2-4a38aca4db31" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
