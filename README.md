# Mutaito Hackademy
Ethical Hacking &amp; OSINT courseware program. 

Intended for low technical profiles, free of charge presencial classes @Barcelona, Spain for whom do not own studies, certification or diplomas. 


1) Hardware, OS and Architecture: Introduction
- Introduction differents hardware: PC, Android, Server, Raspberry, IoT,Modem, Router, Switch, Firewall.
- Introduction differents Architecture and OSes: x86, X64, ARM, WIN SERV, UBUNTU, RASBIAN

Practices: 
- Unbuild and identify parts and components of a Dell PowerEdge 2950
- Install a Fresh Ubuntu
- Install Rasbian on a raspberry


                                                        ----------------------------------


2) Network & infrastructure: Introduction
- Introduction to network from Macro to Micro: Web to local network
- Technical principles: IP/RANGE, DNS, DHCP, Router, Switch, Firewall, IDS / IPS, VPN, TOR.
- Secure Online Navigation: Encryption capsule principles.

Practices:
- Set up a network using a Modem, a router and DHCP
- Establish a IP Plan with the class computers
- Assign static IP to computers as per the IP Plan
- Deploy a firewall
- Login and connect to the firewall
- Look up for the rules and trigger alerts. 

Scenario:
You have been assigned the set up of an office network including various devices such as servers, computers, firewalls and IoT devices.
Once the netwok designed and planned you will have to deploy it´s infrastructure including modem, router, switches and connect the devices as per their IP Plan, computers, servers, mobile devices including all OSes , Mac, Windows, Linux, Android. 
Once the network you will have to locate in the firewall the established rules and accordingly trigger alerts.   

                                                         ----------------------------------


3) Web and Technologies: Introduction
- Introduction to Webapp and DBs
- Discovery of technologies and webapps with DOJO & DVWA VM
- Presentation DB & Dumps

Practices:
- Create a DB with class elements
- Perform a vulnerability assesment on a website
- Hack the website´s DB

Scenario:
You have been tasked with performing a vulnerability assesment on a website and find SQL injection entry point, once located you must gain access to the database and dump it on your local drive. 


                                                         ----------------------------------


4) Hardware, OS and Architecture: Level 1
- Linux Kali: SSH, Bash & Terminal principles
- Windows: Server 2016, Install and config
- Android: Root a device

Practices:
- Terminal navigation, install from APT, Install github clone, chmod, execute a software
- Clone the class github repository into /OPT/HACKADEMY from the terminal
- Install and configure a windows server 2003 with IIS capacity
- Scan the windows server 2003 for vulnerabilities and exploit
- Root an android device


                                                         ----------------------------------


5) Network & infrastructure: Level 1
- Different connections and protocol to network: TCP / UDP / RDP / WIFI / WEP / WPA ...
- Network Scan and Recon principles
- NMAP - ZENMAP introduction

Practices:
- Break WiFi encryption and connect to network
- Scan the network and identify connected device
- Identify the IDS and the Firewall, hack them offline
- Rescan and perform recon on the devices that you found, note the differences.

Scenario:
You have a recognition assignement with no physical access to the assets nor the offices. You must break the wireless encryption, penetrate the network and scan for assets. You will notice that an IDS and a Firewall protects the network, you will have to take them offline and provide accurate details on your network recognition, identifying the devices, opened ports and running services of the devices found on the network will be expected. 

                                                         ----------------------------------


6) Web and Technologies: Level 1
- CMS, APACHE, TOMCAT, PHP, MYSQL intro
- Vulnerabilities in web technologies, how to identify them

Practices:
- Scan the webserver and identify the technologies 
- Find the vulnerabilities related to the webapps
- Document the vulnerabilities

Scenario:
You have been assigned a web application recognition in order to prepare a further attack, you must create a detail report on all vulnerabilities you have found, document them with the ressources you have discovered during the class. All vulnerabilities must be documented with the corresponding CVE reference and level of criticity.

                                                         ----------------------------------


7) Hardware, OS and Architecture:  Level 2
- Corporate / Infrastructure networks
- Network protocols FTP, TELNET, RDP and their vulnerabilities
- BruteForce and Password list generator

Practices :
- 2 Teams: Osint & Hack
- Osint practice recon on infrastructure target, Hack team performs penetration into network
- Osint Team must find the login and password hint
- Hack Team create the password list given Osint provided intels
- Hack Team launch brute force attack against FTP, TELNET, RDP protocols and available devices.

Scenario: 
In this scenario the class will be divided in two teams, one team will be tasked with hacking (Hacking Team) the second team will provide intelligence support (Osint Team). The objective of this scenario is to retrieve a file on a server, while the Osint Team investigate the target in order to find hint and generate the materials for the Hack Team (Password list, Recon Intel, Company users etc...). During this time the Hack team will have to penetrate the network, scan it and identify the services that will allow them to eventually retrive the file. The Osint Team should have by then provided the materials needed to bruteforce into the suspected services and/or devices. Once located, retrieve the file in local. 

----------------------------------
 

Requirements for class:
- Laptop decent enough to run a VirtualBox
- 1 x USB Key (>32GB)
- 1 x Wifi USB dongle compatible Kali (Amazon +/-4€)


TO DO:
- classify ressources
- Centralize VMs
- Build up courseware
- Deploy Lab
- Set up scenarios
