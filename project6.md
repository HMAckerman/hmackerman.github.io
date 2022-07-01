[Back to Portfolio](./)

pfSense w/ Snort IDS Setup and Log4j Exploit and Monitoring
===========================================================

-   **Class: CSCI 352** 
-   **Grade: 102.00**
-   **Project Document: [pfSense Setup Doc](/pdf/pfSense.pdf)**

## Project description
This project was a team-based project, where my team and I were tasked with putting together a hands-on exercise for the rest of the class to complete. This 
project utilized the pfSense firewall package and the Snort IDS/IPS software extension. The students were tasked with installation and setup of the pfSense 
machine, and assigning a static IP address to the WAN and LAN adapters. The students were also tasked with setting up the Snort software suite, downloading
threat signatures and verifying the MD5 hash of the signatures. Then, the students were told to run a ping command in the CLI against a site, and were told to 
record their findings from the Snort package. As extra credit, I provided students with the opportunity to run the Log4j exploit against a dockerized vulnerable 
web app, and detect the exploit through Snort.

## UI Design

This project's UI revolved around the VirtualBox virtualization software and running the disk images for pfSense and a Linux distro disk image. They were 
required to be on the same subnet, so the Linux box could access the pfSense setup wizard. The following screenshots will showcase aspects of the project.

![pfSense 1](images/pfsense1.jpg)<br>
Fig 1. This is the main interface of the pfSense box.

![pfSense 2](images/pfsense2.jpg)<br>
Fig 2. This is the main setup wizard served through an internally hosted webserver in the pfSense package.

![pfSense 3](images/pfsense3.jpg)<br>
Fig 3. This is the installation of the Snort IDS/IPS suite.

![pfSense 4](images/pfsense4.jpg)<br>
Fig 4. This is the downloading of the threat signatures.

![pfSense 5](images/pfsense5.jpg)<br>
Fig 5. This is the enabling of the threat signatures.

![pfSense 6](images/pfsense6.jpg)<br>
Fig 6. The user pings a site, and the Snort suite alerts to the pings. 

Log4j Exploit
=============

![pfSense 7](images/pfsense7.jpg)<br>
Fig 7. The user clones a git repo of a vulnerable docker app.

![pfSense 8](images/pfsense8.jpg)<br>
Fig 8. The user builds the vulnerable app.

![pfSense 9](images/pfsense9.jpg)<br>
Fig 9. The user runs the vulnerable app.

![pfSense 10](images/pfsense10.jpg)<br>
Fig 10. On Kali Linux, the user sets up a malicious LDAP server.

![pfSense 11](images/pfsense11.jpg)<br>
Fig 11. The user does recon of the Ubuntu box hosting the vulnerable app.

![pfSense 12](images/pfsense12.jpg)<br>
Fig 12. The user exploits the Log4j vulnerability.

![pfSense 13](images/pfsense13.jpg)<br>
Fig 13. Snort alerts to the exploit.

## Additional Considerations
I primarily worked on setting up the machines, but I could not have done this project without the help of Lexa Mosby and Brian Diaz. I could not have asked 
for better teammates. Due to their stellar work, our project was voted as the favorite among the students, hence why we received a 102. 
