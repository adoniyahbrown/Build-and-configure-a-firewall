# Build And Configure A Firewall

## Objective
Brief Objective 

Building and configuring a firerall is crucial for protecting networks from unauthorized access and potential threats. This tutorial will guide you through setting up and configuring a firewall on an Ubuntu system using UFW ( Uncomplicated Firewall). 
### Skills Learned

- Advanced understanding of Linux commands.
- Proficiency in analyzing and interpreting network logs.
- Ability to generate and recognize attack signatures and patterns.
- Enhanced knowledge of network protocols and security vulnerabilities.
- Development of critical thinking and problem-solving skills in cybersecurity.

### Tools Used

- Security Information and Event Management (SIEM) system for log ingestion and analysis.
- Network analysis tools (such as Wireshark) for capturing and examining network traffic.
- Telemetry generation tools to create realistic network traffic and attack scenarios.

## Steps
 Step 1: Update your System
 
 Ensure your system is up to date.

 https://imgur.com/a/embsmUP
 
 https://imgur.com/a/tPdOehS

 https://imgur.com/a/VlMnwVs

 https://imgur.com/a/eHN5RAv

Step 2: Install UFW 

https://imgur.com/a/56hP75F

https://imgur.com/a/EZoAz04

Step 3: Enable UFW

https://imgur.com/a/7UuQDdf

https://imgur.com/a/YRJV7Rz

Step 4: Allow SSH Connections

https://imgur.com/a/I97RIGP

https://imgur.com/a/kymoReR

Alternatively, you can specify the port number (default is 22)

https://imgur.com/a/rOW0sOC

https://imgur.com/a/12OoQZ6

Step 5: Allow Specific Services and Ports
1. Allow HTTP AND HTTPS traffic:

   HTTP:

   https://imgur.com/a/AoPoUP8
 
   Rule added:
   
   https://imgur.com/a/qupuRTe

   HTTPS:
   
   https://imgur.com/a/I7MBnHn

   Rule added:

   https://imgur.com/a/R7U43cJ

   Port 80 TCP:

   https://imgur.com/a/qD1uOxn

   Rule added:

   https://imgur.com/a/XuBRsDS

   Port 443 TCP:

   https://imgur.com/a/ViX90lg

   Rule added:

   https://imgur.com/a/93jNtzW

   Port 8080 TCP:

   https://imgur.com/a/PSvZejk

   Rule Added:

   https://imgur.com/a/idRIfmL

   Port 1000:2000 TCP:

   https://imgur.com/a/o0kDn1h

   Rule Added:

   https://imgur.com/a/6Ca5ANL

   IP Adresses 192.168.1.100:

   https://imgur.com/a/A5Dhj5h

   Rule Added:

   https://imgur.com/a/UOvijXg

   
SubNet 192.168.1.0/24:

https://imgur.com/a/9fsyQjs

Rule Added: 

https://imgur.com/a/rjFGERX

Step 6: Deny Specific Services and Ports:

Deny a specific port 23 TCP:

https://imgur.com/a/GfMf8g7

Rule Added:

https://imgur.com/a/3OMZIYm

Deny a specific IP address 203.0.113.0:

https://imgur.com/a/IjcO80J

Rule Added:

https://imgur.com/a/3hZWFFX

Step 7: View UFW Status and Rules:

https://imgur.com/a/PP8kC9G

Rule Added:

https://imgur.com/a/KKID7QL

Step 8: Delete UFW Rules:

Using rule number:

https://imgur.com/a/tZHoFMl

Numbers Displayed:

https://imgur.com/a/VTe9NKF

Delete a rule by specifiying its number:

https://imgur.com/a/fSyXMvu

Delete a rule by specifying its number yes or no:

https://imgur.com/a/x3djITx

Delete a rule by specifying its number deleted rule:

https://imgur.com/a/pPU2025


Delete allow 8080 TCP:

https://imgur.com/a/mLJf4Z8

Allow 8080 TCP Rule Deleted:

https://imgur.com/a/bms8yY5

Step 9: Advanced UFW Configuration 

Logging:

https://imgur.com/a/tBV6Dyj

Logging enabled:

https://imgur.com/a/ocv1J9D

Default Policies:

Deny Incoming: 

https://imgur.com/a/bgyDP2T

Deny Incoming Policy Added:

https://imgur.com/a/ajmYDfY

Allow Outgoing: 

https://imgur.com/a/rGqQgua

Allow Outgoing Policy Added:

https://imgur.com/a/fhJzsyK


Application Profiles:

App List:

https://imgur.com/a/DCUvkGN

App List rules added: 

https://imgur.com/a/TuEcHbM

Allow a specific application:

'Nginx Full'

https://imgur.com/a/GeGQx7i

'Nginx Full'  Rules Added:

https://imgur.com/a/llA4I3A

Step 10: Testing the Firewall

Check Open Ports:

https://imgur.com/a/ic8IHO3

Sudo  Snap Install Software Nmap:

https://imgur.com/a/9oeGjNC

Nmap Software Installed:

https://imgur.com/a/O3bAw3E

Re-run Nmap IP after installed software:

https://imgur.com/a/xnneTb2

Host Down:

https://imgur.com/a/c1N3X4B

Check Connection:

https://imgur.com/AYkqqfN

Step 11: Document Your Setup

Configuration Details:

https://imgur.com/a/DrYt8M5











   

   

   


 



 
