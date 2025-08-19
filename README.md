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

<img width="911" height="738" alt="image" src="https://github.com/user-attachments/assets/5738181c-dce0-458c-8b42-afe9500d3663" />

### Finding Hosting Company :


<img width="1617" height="847" alt="image" src="https://github.com/user-attachments/assets/785c5332-534a-4754-85d0-645e2ecb075e" />


### History of the website :


<img width="1919" height="922" alt="image" src="https://github.com/user-attachments/assets/3fd65f7b-6a24-41dc-b8b5-f1aee477132a" />


### ping command :
<img width="735" height="694" alt="image" src="https://github.com/user-attachments/assets/354b4935-5a03-4c5f-8637-b7b749d157a4" />


### whois :

<img width="760" height="742" alt="image" src="https://github.com/user-attachments/assets/79694cd4-c12c-4d63-b313-913e1506a733" />


### netcat :

<img width="665" height="108" alt="image" src="https://github.com/user-attachments/assets/bb93be15-acb6-4473-bc3b-590e015f712c" />

### nmap :

<img width="637" height="261" alt="image" src="https://github.com/user-attachments/assets/37659d82-c9f5-47c1-a5bc-4baff004e2db" />


### whatweb :

<img width="745" height="197" alt="image" src="https://github.com/user-attachments/assets/928a6c89-b160-421c-add3-4dd7bd400aa0" />


### httprint :

<img width="630" height="208" alt="image" src="https://github.com/user-attachments/assets/25d1d98e-6ccd-4459-957f-c91ac4edd97e" />


### TCP traceroute :

<img width="747" height="394" alt="image" src="https://github.com/user-attachments/assets/c957bd67-1b5e-42ba-baee-1fa5332cbb47" />


### UDP traceroute :

<img width="731" height="527" alt="image" src="https://github.com/user-attachments/assets/7478e1f6-9ed0-4a13-8629-fed1faa85635" />


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
