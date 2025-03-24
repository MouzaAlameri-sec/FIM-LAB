<h1> Using Wazuh platform to enforce File Integrity Monitoring </h1>



<h2>Description</h2>
This lab project is part of my preparation for the CompTIA Security+ certification. It’s a hands-on project that implements key concepts like SIEM (Security Information and Event Management) — a system that monitors and analyzes logs to detect suspicious behavior. This includes file monitoring, where alerts are triggered if files are modified, accessed, or deleted unexpectedly.

For this project, we’ll be using Wazuh, an open-source SIEM platform that provides real-time threat detection, log analysis, and security monitoring.

NOTE. Screenshots would include name and date to ensure integrity of work. (This lab is done in ACI Learning environment) To test this lab realistically you would need to set up the envrionmenets used in vmware / virtual mechine. 
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Diskpart</b>

<h2>Environments Used </h2>
Windows Server 2022 - Domain Controller
Windows 11 PRO - Domain Member Workstation
Alma Linux 9.1 - Stand-alone Linux Server

- <b>    </b> (21H2)

<h2>Program walk-through:</h2>

<p align="center">
: <br/>
<img src="Screenshot 2025-03-24 200305.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Select the disk:  <br/>
<img src="https://i.imgur.com/tcTyMUE.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Enter the number of passes: <br/>
<img src="https://i.imgur.com/nCIbXbg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Confirm your selection:  <br/>
<img src="https://i.imgur.com/cdFHBiU.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src="https://i.imgur.com/JL945Ga.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Sanitization complete:  <br/>
<img src="https://i.imgur.com/K71yaM2.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src="https://i.imgur.com/AeZkvFQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
