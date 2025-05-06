# Cybersecurity-lab4
1. Basic Vulnerability Scan using Nessus

   1.Start Nessus
   
   2.Create a new scan:we create new scan folder and we use "Basic Network Scan":Scans > New Scan > Basic Network Scan
   
   3.Scan Settings:we named our new folder "Lab 4" and save and "launch the scan"
![image alt](https://github.com/AlizadaUlvi/Cybersecurity-lab4/blob/3b3098f10efd47d30cd10f9a387ef0f3d411674f/step1/step1.jpg)
![image alt](https://github.com/AlizadaUlvi/Cybersecurity-lab4/blob/cc1608c4f2f8cf3a36aa6c09494ea98022181938/step1/step1%20(2).jpg)
![image alt](https://github.com/AlizadaUlvi/Cybersecurity-lab4/blob/436153cc154a00d1561767e48250e619b788fea9/step1/step1%20(3).jpg)
![image alt](https://github.com/AlizadaUlvi/Cybersecurity-lab4/blob/09bc0acee2ef3c452692cc92bf95ab5b4193f119/step1/step1%20(4).jpg)

2.Analyze Scan Results

      a.Review vulnerabilities
      
         1.Open the report by clicking the scan name.
   
         2.Sort vulnerabilities Severity
![image alt](https://github.com/AlizadaUlvi/Cybersecurity-lab4/blob/de090274da6953a17f93bdce321fb00385256985/step2/step%202%20a.jpg)
![image alt](https://github.com/AlizadaUlvi/Cybersecurity-lab4/blob/aa75ac2de26ea395e636b716e04c31970b98df20/step2/step%202%20a%20(2).jpg)   
There are 2 Medium and 11 Info vulnerabilities
       
       b.Drill down into a few vulnerabilities:
          
          1.Description,CVE ID,Exploitability,Suggested Fix
          
![image alt](https://github.com/AlizadaUlvi/Cybersecurity-lab4/blob/cb0080d7c7f4d25f6b1cc5df31b4597648f4e6c3/step2/step%202%20b.jpg)
![image alt](https://github.com/AlizadaUlvi/Cybersecurity-lab4/blob/4b38d7a6e2ba952b05fb3c9452f749ec374bd9ba/step2/step%202%20b%20(2).jpg)
For example in picture 1:

A medium-severity vulnerability ("SMB Signing not required")

The description, solution, and plugin details

The CVSS score (5.3) and risk information

Affected port (445/tcp) and host IP (192.168.0.117)

Exploit availability marked as true

In picture 2:

Severity: Medium

CVSS Score: 5.0

Host Affected: 192.168.0.117

Port: UDP 5353
