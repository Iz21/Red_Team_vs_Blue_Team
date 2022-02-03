# Red_Team_vs_Blue_Team_Project
A Red vs Blue Teams project to run through an exercise of exploiting vulnerable machines and capturing log data with Kibana for the purpose of ultimately being able to create alerts for future potential exploitations, all through the use of Virtual Machines in an Azure Cloud environment
## Project Overview
This document contains the following details:
- Description of the Topology 
- Red Team Attack Overview
   - Nmap Scan
   - Webserver Nagivation
   - Vulnerability Scan 
   - Bruteforce
   - SSH
   - Flag 1
   - Passward Hash and Crackstation tool
   - Webdav
   - Reverse Shell
    - Msfvenom
    - Cadaver ?   
    - Metasploit
   - Interactive Shell Access
    - Flag 2
    - Exfiltration  
   - Vulnerabilities
- Blue Team Identification and Alert Workflow Overview
   - Nmap Discovery
   - Brute Force Discover (i.e. Hydra)
   -  WebDav Discovery/Connections
   -  Alerts and Mitigation Strategies
## Network Topology 

### Overview
![Network Topology](https://github.com/Iz21/Red_Team_vs_Blue_Team_Project/blob/a4d09a5259b0b2dc8cb61ad4547e1943001a2c1b/Images/Red_vs_Blue_Team_Network%20diagram_Overview.PNG)

### RED Team Attack Network Map:
![Red Team Topology](https://github.com/Iz21/Red_Team_vs_Blue_Team_Project/blob/f7923b5d174e399368492385c48e0ad8c4a9c736/Images/Red%20Team_Github.PNG)

### BLUE Team Defense Network Map:
![Blue Team Topology](https://github.com/Iz21/Red_Team_vs_Blue_Team_Project/blob/48a69c5c165d094867d38cf322694bd238a7e7eb/Images/Blue%20Team_Github.PNG)

#### Nmap identification of hosts on network:
![Nmap VM IPs](https://github.com/Iz21/Red_Team_vs_Blue_Team_Project/blob/c106136047cd3763455e7d8e2652e755e79dd354/Images/VM%20IPs.png)


# Red Team Penetration Test

### 1. Find IP address of Kali Linux machine:
![Find IP address of Kali Linux](https://github.com/Iz21/Red_Team_vs_Blue_Team_Project/blob/eee37f6d9bf01ea896a992934054755604028d5f/Images/Find%20IP%20address%20of%20Kali%20Linux.png)

### 2. Run Nmap on Kali Linux machine to find open port 80
![Run Nmap on Kali Linux to find open port](https://github.com/Iz21/Red_Team_vs_Blue_Team_Project/blob/cb2c41880d6df06a2004f1d9a04aa24882dfe576/Images/Run%20Nmap%20on%20Kali%20LInux.png)

## Vulnerability Assessment
![Vulnerability Assesment](https://github.com/Iz21/Red_Team_vs_Blue_Team_Project/blob/29894624dda55031ee725a0c840545c5fac27198/Images/Vulnerablitiy%20Assessment.png)
![Vulnerability Assesmentt2](https://github.com/Iz21/Red_Team_vs_Blue_Team_Project/blob/609f328b2fb69cd82759bfc3bfcf713a2c6e7bef/Images/Vulnerablitiy%20Assessment2.png)

## Exploitations
![Exploitation 1](https://github.com/Iz21/Red_Team_vs_Blue_Team_Project/blob/ebe0df1cd467ca7cb0030636084715c02cbe9feb/Images/Exploitation%20slide.png)
![Exploitation 2](https://github.com/Iz21/Red_Team_vs_Blue_Team_Project/blob/ebe0df1cd467ca7cb0030636084715c02cbe9feb/Images/Exploitation%20slide2.png)
![Exploitation 3](https://github.com/Iz21/Red_Team_vs_Blue_Team_Project/blob/ebe0df1cd467ca7cb0030636084715c02cbe9feb/Images/Exploitation%20slide3.png)










